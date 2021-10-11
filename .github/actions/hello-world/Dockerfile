FROM golang:1.15
WORKDIR /go/src/hello
RUN pwd
RUN ls
COPY . .
RUN pwd
RUN ls
RUN go get -d -v ./...
RUN go install -v ./...
CMD ["hello"]
