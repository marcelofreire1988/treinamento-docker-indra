FROM golang as go

WORKDIR /app

ADD . /app

RUN go build -o hello-go


FROM alpine

WORKDIR /app

COPY --from=go /app/hello-go /app

ENTRYPOINT ./hello-go

