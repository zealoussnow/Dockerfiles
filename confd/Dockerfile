FROM golang:1.11.13-buster

RUN apt install -y make git gcc g++
RUN mkdir -p /go/src/github.com/kelseyhightower/confd && \
  ln -s /go/src/github.com/kelseyhightower/confd /app

WORKDIR /app
