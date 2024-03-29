
# Hello Node from Docker

A Demo project for running node/express app using docker


## Run app using docker

clone this repo

```bash
git clone https://github.com/ankitgadling/hello-node-from-docker.git

cd hello-node-from-docker/
```
Build docker image

```bash
docker build -t hello-node .
```
Run docker container with build image

```bash
docker run -d -p 3000:3000 hello-node
```
stop docker container

```bash
docker stop <container_id_or_name>
```
find conatiner_id using following command

```bash
docker ps
```
    