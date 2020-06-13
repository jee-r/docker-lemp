# docker-lemp
**L**inux + Nginx (**E**ngine-X) + **M**ysql + **P**HP
Build Status : [![Build Status](https://cloud.drone.io/api/badges/jee-r/docker-lemp/status.svg)](https://cloud.drone.io/jee-r/docker-lemp)

I build this for my personnel use because i can't find anywhere a functionnal scaled docker LEMP stack.

## Image Specs

|Image|php-fpm|
|-	|-	|
|Base image| [alpine:3.12](https://hub.docker.com/_/alpine) |
|Default User ID|1000|
|Default Group ID|1000|

|Image|nginx|
|-	|-	|
|Base image| [nginxinc/nginx-unprivileged:latest](https://hub.docker.com/r/nginxinc/nginx-unprivileged) |
|Default User ID|101|
|Default Group ID|1000|

|Image|db|
|-	|-	|
|Base image| [mariadb:latest](https://hub.docker.com/_/maridb) |
|Default User ID|1000|
|Default Group ID|1000|
