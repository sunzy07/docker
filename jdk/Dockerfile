FROM openjdk:8-jdk-alpine
 
ENV LANG en_US.UTF-8

EXPOSE 80
EXPOSE 8443
EXPOSE 8883
 
RUN apk add --update ttf-dejavu fontconfig && rm -rf /var/cache/apk/* && cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime && echo Asia/Shanghai > /etc/timezone

