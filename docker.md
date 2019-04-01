---
layout: page
title: docker
docs: https://www.docker.com/ 
---
From a dockerfile to a docker image 
```bash
docker build -t <image name> .
```
How to create a docker "container"
```bash
docker run <image name>
```
A short summery about docker\:
- A `Dockerfile` is a recipe for creating Docker images
- A Docker image gets built by running a Docker command (which uses that `Dockerfile`)
- A Docker container is a running instance of a Docker image
