# Docker Compose Guide

## 1. What does the `services:` block do?

The `services:` block defines the containers needed for the application. In this project, it specifies the Nextcloud application and its database, including their configurations and settings.

## 2. How does Nextcloud find the database container?

Nextcloud connects to the database through the `MYSQL_HOST` environment variable. This variable contains the database service name defined in the Compose file. Docker Compose provides internal networking, allowing Nextcloud to communicate with the database using that service name.

## 3. Difference between `docker run` and `docker-compose up -d`

The `docker run` command starts an individual container using commands entered manually. In contrast, `docker-compose up -d` reads the `docker-compose.yml` file and starts all defined services together in the background. Docker Compose makes deployment easier because the configuration can be reused without repeatedly entering long commands.

