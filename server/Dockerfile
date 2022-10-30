FROM golang:1.16-alpine

WORKDIR /home/blog/server

COPY . .

EXPOSE 5000

RUN GOOS=linux GOARCH=amd64 go build -o main

CMD [ "./main" ]
