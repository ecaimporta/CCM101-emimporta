# Laboratory 04 — Cloud-Native Engineer

## Mission Overview

This laboratory activity introduced cloud-native engineering and containerization using Docker in KillerCoda. The activity focused on understanding the difference between Virtual Machines and Containers, deploying an Nginx web server, and managing the container lifecycle.

## Objectives

- Differentiate Virtual Machines and Containers.
- Use Docker commands in KillerCoda.
- Deploy an Nginx container.
- Manage container lifecycle operations.
- Document the activity using Markdown.

## Docker Commands Executed

```bash
docker --version
docker info
docker pull nginx
docker run -d --name nginx-server -p 8080:80 nginx
docker ps
curl http://localhost:8080
docker stop nginx-server
docker ps -a
docker rm nginx-server
```

## Skills Learned

- Basic Docker commands
- Container deployment
- Port mapping
- Nginx deployment
- Container lifecycle management
- Markdown documentation

## Challenges Encountered

One challenge I encountered was understanding how Docker containers work and how port mapping connects the host machine to the container. I also learned the importance of checking container status using Docker commands.
