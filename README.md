# Wordpress Docker Compose
This repository has the [**Docker Compose file**](docker-compose.yml) to create a WordPress project.

## Download and Deploy
The first time, the database user is created, you must wait around a minute and now you can start edit your WordPress project deployed in **localhost**.
```bash
git clone https://github.com/atriox2510/wordpress-docker
cd wordpress-docker
docker-compose up -d
```
**Note:** the [Web Directory: www](www) contains the PHP files than WordPress use for the plugins, themes, etc. When you download the repository this directory will be empty, when you start **docker-compose** this folder would gona fill.
