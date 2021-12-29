FROM golang:1.14.9-alpine AS builder
RUN mkdir /build
ADD go.mod go.sum app.go /build/
WORKDIR /build
RUN go build
CMD ["./helloworld"]