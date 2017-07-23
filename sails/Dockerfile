FROM node:8-alpine
LABEL maintainer="Leo <zmliu@gmail.com>"

RUN npm install sails@0.12.3 grunt-cli bower pm2 -g --registry=https://registry.npm.taobao.org

VOLUME ["/app"]

WORKDIR /app