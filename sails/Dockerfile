FROM node:8-alpine
LABEL maintainer="Leo <zmliu@gmail.com>"

RUN npm install grunt-cli bower pm2 -g

VOLUME ["/app"]

WORKDIR /app

# Start process.yml
CMD ["http-server"]