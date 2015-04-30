# docker-haproxy-ssl
Lean (9MB) HAProxy + SSL termination Docker image, based on `progrium/busybox`.

## Current software

* HAProxy 1.5.11-patch02

## Pre-requisites

* Docker 1.5.0+ (tested with boot2docker)

## Build images (optional)

Providing your own version of [the image automatically built for Logstash](https://registry.hub.docker.com/u/pires/docker-haproxy-ssl) will not be supported. This is an *optional* step. You have been warned.

```
git clone https://github.com/pires/docker-haproxy-ssl.git
cd docker-haproxy-ssl
docker build -t pires/docker-haproxy-ssl .
```