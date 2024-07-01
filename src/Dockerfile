FROM docker.io/library/alpine:latest as runner

RUN set -ex; \
  apk update; \
  apk add gcc gcompat icu-dev icu-libs musl-dev tzdata;
