# Wordpress Docker Compose
Wordpress with Docker Compose and MariaDB

This repository has the [**Docker Compose file**](docker-compose.yml) to create a WordPress project.

## Download and Deploy
```bash
git clone https://github.com/marcopat01/wordpress-docker-compose
cd wordpress-docker-compose
docker-compose up -d
```
The first time, the database user is created, you must wait around a minute and now you can start edit your WordPress project deployed in **localhost**.
**Note:** the [Web Directory: www](www) contains the PHP files than WordPress use for the plugins, themes, etc. When you download the repository this directory will be empty, when you start **docker-compose** this folder would gona fill.
