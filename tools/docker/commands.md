# 🐳 Docker Commands Cheat Sheet

## 📦 Image Commands

```bash
docker build -t myapp .
docker images
docker rmi <image_id>

## 🚢 Container Commands

```bash
docker run -d -p 8080:80 nginx
docker ps -a
docker exec -it <container_id> bash

## 🧹 Cleanup

```bash
docker system prune
docker volume ls
docker network ls


## 📖 Info Commands


```bash
docker version
docker info
docker inspect <image_name or container_id>

## 🔚 Stop & Remove Containers


```bash
docker stop <container_id>
docker rm <container_id>
docker container prune

