FROM node:8-alpine
LABEL maintainer="Leo <zmliu@gmail.com>"

RUN npm install grunt-cli bower pm2 -g --registry=https://registry.npm.taobao.org

VOLUME ["/app"]

WORKDIR /app