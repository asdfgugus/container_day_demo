FROM alpine:latest

LABEL maintainer="janick.kaenzig@post.ch"

WORKDIR /

RUN apk add --no-cache bash

COPY ./script.sh /

RUN chmod 751 script.sh

CMD "/script.sh"

