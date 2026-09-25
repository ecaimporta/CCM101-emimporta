# Laboratory 06 Reflection

Writing the docker-compose.yml file made the deployment process more manageable because the configuration for the application and database was placed in one file. Instead of manually entering separate settings for each container, Docker Compose could read the YAML file and create the required services together. This showed me how Infrastructure as Code can make cloud deployment more organized and repeatable.

I also learned why YAML indentation needs to be checked carefully. YAML depends on spaces to identify the relationship between different parts of the configuration. If a Tab is used or the spacing is incorrect, Docker Compose may not understand the file correctly and the deployment can fail. This made me realize that even formatting is important when working with configuration files.

Environment variables such as MYSQL_PASSWORD were included because the containers need specific database information to communicate properly. The password, database name, username, and database host are passed to the application through the Compose configuration. This allows the Nextcloud container to use the MariaDB service with the required settings.

Deploying Nextcloud in only a few minutes was a useful experience because I could see how several cloud components could be prepared through a small configuration file. After starting the services, accessing the Nextcloud setup page made the deployment feel more practical than simply working with commands in the terminal.

Since Mission 1, my understanding of Cloud Computing has become broader. I now have a better idea of how Linux, containers, networking, databases, storage, and automation are connected in a cloud environment. This mission also helped me understand that cloud engineers need to document and automate their infrastructure instead of relying only on manual commands.
