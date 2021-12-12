FROM golang:latest
WORKDIR /app

RUN go get -v github.com/google/uuid
RUN go get -v github.com/gorilla/websocket

COPY ./rop1 /app/rop1

EXPOSE 8080

CMD ["for { }"]
ENTRYPOINT ["./rop1"]
