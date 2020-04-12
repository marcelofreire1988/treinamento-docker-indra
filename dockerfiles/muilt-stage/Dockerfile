FROM golang

WORKDIR /app
ADD . /app
RUN go build -o hello-go
ENTRYPOINT ./hello-go
