FROM nginx:stable-alpine

RUN  apk add --upgrade --no-cache tzdata \
     && rm -rf /var/cache/apk/* /tmp/*

ENV  TZ=Europe/Bucharest

COPY ./default.conf /etc/nginx/conf.d/default.conf