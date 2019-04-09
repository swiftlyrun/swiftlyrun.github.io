---
layout: page
title: docker
docs: https://docs.docker.com/
---
Build Docker image `image_name` from dockerfile `Dockerfile` 
```bash
docker build -t image_name .
```
Create and start a Docker container from image `image_name`
```bash
docker run image_name
```
A short summary of docker:
- A `Dockerfile` is a 'recipe' for creating Docker images
- A Docker image gets built by running the `docker build` command (which uses the aforementioned `Dockerfile`)
- A Docker container is a running instance of a Docker image
- Docker images consist of layers. Each `Dockerfile` instruction turns into it's own layer.
- When (re-)building an image, unchanged layers are simply reused, which can drastically reduce build time.
