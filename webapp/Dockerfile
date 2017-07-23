FROM node:8-alpine
LABEL maintainer="Leo <zmliu@gmail.com>"

RUN npm install http-server -g

VOLUME ["/app"]

WORKDIR /app

# Start process.yml
CMD ["http-server"]