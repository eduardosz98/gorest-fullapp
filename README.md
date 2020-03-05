# Dockerized-Golang-Postgres/Mysql-API

## Build and deploy in containers
docker-compose up --build -d

## Get db container_id
docker container ls

## Get db ip_address
docker inspect container_id

## Configure pgAdmin db server with this ip_address