# Docker Deployment

## Docker Environment

### Check Docker Version

```bash
docker --version
```

This command displays the installed Docker version.

### Check Docker Information

```bash
docker info
```

This command displays Docker system information.

## Nginx Deployment

### Pull Nginx Image

```bash
docker pull nginx
```

This command downloads the official Nginx image.

### Run Nginx Container

```bash
docker run -d --name nginx-server -p 8080:80 nginx
```

This command creates and runs an Nginx container.

### Check Running Containers

```bash
docker ps
```

This command shows running containers.

### Test Nginx

```bash
curl http://localhost:8080
```

This command verifies that the Nginx server is working.

## Container Lifecycle

### Stop Container

```bash
docker stop nginx-server
```

This command stops the container.

### View All Containers

```bash
docker ps -a
```

This command displays all containers.

### Remove Container

```bash
docker rm nginx-server
```

This command removes the stopped container.
