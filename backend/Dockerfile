FROM golang:1.12 AS build
RUN mkdir /app
ADD . /app/
WORKDIR /app
RUN go get -d
RUN go build -o main
CMD ["/app/main"]