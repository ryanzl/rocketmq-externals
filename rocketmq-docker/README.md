# Apache RocketMQ Docker module

Apache RocketMQ Docker module provides Dockerfiles and scripts for RocketMQ.

This repository includes the following:

1. Dockerfile and scripts for RocketMQ base image;
2. Dockerfile and scripts for RocketMQ run in following 3 scenarios:
- RocketMQ runs on single Docker daemon;
- RocketMQ runs with docker-compose;
- RocketMQ runs on Kubernetes.

## Quick start: Build and run RocketMQ with a single instance

### For Docker

Run:

```
cd 4.2.0

./play-docker.sh

```

### For docker-compose

Run:

```
cd 4.2.0

./play-docker-compose.sh
修改了配置，重新运行也是使用这个命令

```


### For Kubernetes

Run:

```
cd 4.2.0

./play-kubernetes.sh

```
