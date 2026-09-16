# Docker Deployment

## Docker Commands Used

### Check Docker Version

sudo docker --version

### Pull NGINX Image

sudo docker pull nginx

### Run NGINX Container

sudo docker run -d --name nginx-lab -p 8080:80 nginx

### Check Running Container

sudo docker ps

### Stop Container

sudo docker stop nginx-lab

### Check All Containers

sudo docker ps -a

### Remove Container

sudo docker rm nginx-lab

## Summary

The activity demonstrated the basic Docker container lifecycle. The NGINX image was downloaded, a container was created and started, the container status was checked, and the container was stopped and removed.
