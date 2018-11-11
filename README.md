# Wordpress Docker
Wordpress development workflow using Docker.

## Prerequisites
- Docker for your Host Computer [Mac](https://docs.docker.com/docker-for-mac/install/) [Windows](https://docs.docker.com/docker-for-windows/install/)

## Quickstart
1. Clone this repository.
2. Navigate to project root, run `docker-compose down -v && docker-compose up -d --build` to start the docker container group.
3. Navigate to http://localhost

## Connecting to the database
- Using your favorite MySQL client, setup a connection with the ff details:
    - HOST: **localhost**
    - PORT: **3306**
    - USERNAME: **dockerwp_user**
    - PASSWORD: **wordpress**

**Note: Check the `docker-compose.yml` file on how this is handled in Docker**
