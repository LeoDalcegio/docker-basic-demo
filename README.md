# Docker + Node.js

Dockerize a Node.js app.

Dockerfile - Blueprint to build a Docker Image

Image - Template for running Docker Containers

Container - Running process of and image

---

` docker build -t leodalcegio/demoapp:1.0 .`

!!! Will not "work"

` docker run c37029f94553`

!!! For port forwarding

` docker run -p 5000:8080 c37029f94553`

Go to loalhost:5000

---

Docker compose - Run multiple containers at the same time

docker-compose.yml

!!! Find this file and run all the containers together

` docker-compose up`

Watch the full [Docker video](https://youtu.be/gAkwW2tuIqE) on YouTube or read the [Docker Tutorial](https://fireship.io/lessons/docker-basics-tutorial-nodejs/) on Fireship.io.
