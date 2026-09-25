# Docker Compose Guide

## The services: Block

The `services:` block describes the containers that make up the application. In this project, it contains two services: `database` for MariaDB and `app` for Nextcloud.

## How Nextcloud Finds the Database

The Nextcloud container uses the `MYSQL_HOST=database` environment variable. The value `database` matches the name of the MariaDB service in the Compose file, allowing the application to locate the database container through the Docker network.

## docker run vs docker-compose up -d

The `docker run` command can be used to start a single container and specify its settings directly in the command. On the other hand, `docker-compose up -d` reads the configuration from the Compose file and starts the services defined there together in the background.
