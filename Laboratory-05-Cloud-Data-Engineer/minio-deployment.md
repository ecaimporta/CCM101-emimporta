# Deploying My MinIO Object Storage Server

## MinIO Deployment

For this laboratory activity, I deployed MinIO inside a Docker container to create an S3-compatible object storage environment. The MinIO image provided in the activity could not be pulled in the current environment, so I used the available image from `quay.io` while maintaining the required configuration.

## Docker Command

The exact command I successfully used was:

`docker run -d -p 9000:9000 -p 9001:9001 --name minio-server -e "MINIO_ROOT_USER=cloudadmin" -e "MINIO_ROOT_PASSWORD=CloudNova2026!" quay.io/minio/minio server /data --console-address ":9001"`

The container was named `minio-server`. Port `9000` was assigned to the MinIO API, while port `9001` was used to access its web console.

## Accessing MinIO

After the container started, I accessed the MinIO web interface through port `9001`. I logged in using the credentials configured when the Docker container was created.

## Creating Object Storage

Inside MinIO, I created a bucket called `client-photos`. I then uploaded my sample file into this bucket to test whether the object storage server was working properly.

## Environment Variables

The `-e` options were used to provide environment variables to the container. `MINIO_ROOT_USER` configured the root username, while `MINIO_ROOT_PASSWORD` configured the password. These values were available to MinIO when the container started.
