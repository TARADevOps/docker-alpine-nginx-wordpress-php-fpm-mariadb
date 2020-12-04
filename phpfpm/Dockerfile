FROM php:7.3.4-fpm-alpine3.9

RUN apk add --upgrade --no-cache tzdata \
     && rm -rf /var/cache/apk/* /tmp/*

ENV  TZ=Europe/Bucharest

RUN docker-php-ext-install mysqli

ADD ./www.tar.gz  /srv