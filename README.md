# Java Alpine Docker

[![Docker Stars](https://img.shields.io/docker/stars/wolfdeng/java.svg)](https://hub.docker.com/r/wolfdeng/java/)
[![Docker Pulls](https://img.shields.io/docker/pulls/wolfdeng/java.svg)](https://hub.docker.com/r/wolfdeng/java/)
[![Image Size](https://img.shields.io/imagelayers/image-size/wolfdeng/java/latest.svg)](https://imagelayers.io/?images=wolfdeng/java:latest)
[![Image Layers](https://img.shields.io/imagelayers/layers/wolfdeng/java/latest.svg)](https://imagelayers.io/?images=wolfdeng/java:latest)

基于Alpine系统的Java镜像，基础镜像来源于[anapsix/alpine-java:8u144b01_jdk](https://hub.docker.com/r/anapsix/alpine-java/)。

## 使用说明

### 获取镜像
```bash
docker pull wolfdeng/java
```

### 启动容器
```bash
docker run --name java -it -d wolfdeng/java
```

### 使用容器内容的jdk
```bash
docker exec -it java java -version
```
