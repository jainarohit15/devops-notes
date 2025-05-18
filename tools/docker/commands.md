# 🐳 Docker Commands Cheat Sheet

## 📦 Image Commands

docker build -t myapp .
docker images
docker rmi <image_id>

## 🚢 Container Commands

docker run -d -p 8080:80 nginx
docker ps -a
docker exec -it <container_id> bash

## 🧹 Cleanup

docker system prune
docker volume ls
docker network ls


## 📖 Info Commands

docker version
docker info
docker inspect <image_name or container_id>

## 🔚 Stop & Remove Containers

docker stop <container_id>
docker rm <container_id>
docker container prune

