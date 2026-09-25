# Multi-Tier Application Architecture

## Web/Application Tier

The Web/Application Tier is responsible for providing the application that users access through a web browser. In this laboratory, Nextcloud serves as the application and provides the web interface for the private cloud storage system.

## Database Tier

The Database Tier is responsible for keeping the application's persistent information. MariaDB is used in this laboratory as the database that supports the Nextcloud application.

## Why Separate Them?

The web application and database are placed in separate containers so that each service has its own responsibility. This makes the application structure more organized and allows the two services to communicate without placing everything inside one container.
