FROM node:8.16.0-alpine
LABEL MAINTAINER=Sage

COPY . /app
WORKDIR /app

RUN apk upgrade --update \
  && apk add --no-cache build-base \
  && apk add bash \
  && apk add make \
  && npm i -g redoc-cli

CMD touch /app/docs/sample-file-created-in-container.txt

# Build:
# docker build -t finalassignment:latest .

# Run:
# docker run -p 127.0.0.1:8181:8000/tcp --rm \
#        --name finalassignment -t finalassignment:latest

# Stop:
# docker stop finalassignment

# Debug:
# docker run -it finalassignment:latest sh
# or
# docker run -it finalassignment:latest bash