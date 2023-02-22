FROM klakegg/hugo:ext-alpine as build

RUN apk add git && \
  git config --global --add safe.directory /src

COPY .git /.git
COPY ./website /src
WORKDIR /src
RUN hugo

