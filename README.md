
# Hello Node from Docker

A Demo project for running node/express app using docker


clone this repo

```bash
git clone https://github.com/ankitgadling/hello-node-from-docker.git

cd hello-node-from-docker/
```
## Run app using docker

## Option 1

Build docker image

```bash
docker build -t hello-node .
```
Run app using docker container with build image

```bash
docker run -d -p 3000:3000 hello-node
```
Visit app 
```bash
http://127.0.0.1:3000/
```

Stop docker container

```bash
docker stop <container_id_or_name>
```
Find conatiner_id using following command

```bash
docker ps
```
## Option 2

Run app using docker-compose

```bash
docker-compose up -d

```
Visit app 
```bash
http://127.0.0.1:3000/
```

stop app using docker-compose

```bash
docker-compose down

```
    