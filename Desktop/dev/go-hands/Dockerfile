FROM golang:1.22.1-bookworm
RUN apt-get update && apt-get install -y git
RUN mkdir /go/src/app
WORKDIR /go/src/app
ADD . /go/src/app
