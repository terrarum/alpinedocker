# Microcontainers: http://www.iron.io/microcontainers-tiny-portable-containers/
# From: https://github.com/iron-io/dockers/tree/master/base
FROM iron/base:edge
MAINTAINER terrarum@gmail.com

# Update OS.
RUN apk update && apk upgrade

# Install node.
RUN apk add nodejs

# Install ruby.
RUN apk add build-base ruby ruby-dev ruby-json libffi-dev

# Clear package cache.
RUN rm -rf /var/cache/apk/*
