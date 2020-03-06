FROM golang

ENV GO111MODULE=on

RUN mkdir -p /go/src/github.com/user/dalehp/gogrpctest/server

WORKDIR /go/src/github.com/user/dalehp/gogrpctest/server

COPY . .

RUN go install github.com/user/dalehp/gogrpctest/server

ENTRYPOINT ~/go/bin/server