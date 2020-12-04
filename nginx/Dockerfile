FROM nginx:1.15.10-alpine

RUN  apk add --upgrade --no-cache tzdata \
     && rm -rf /var/cache/apk/* /tmp/*

ENV  TZ=Europe/Bucharest

COPY ./default.conf /etc/nginx/conf.d/default.conf