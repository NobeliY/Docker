FROM ubuntu:latest
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y php8.1 php8.1-pgsql php8.1-fpm postgresql-14 nginx
COPY /html/ /var/www/html/
COPY /nginx/ /etc/nginx/
COPY /bash/ /