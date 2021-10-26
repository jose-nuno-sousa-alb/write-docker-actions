FROM golang:latest
WORKDIR /go/src/hello
COPY . .
RUN go mod init
RUN go get -d -v ./...
RUN go install -v ./...
CMD ["hello"]
