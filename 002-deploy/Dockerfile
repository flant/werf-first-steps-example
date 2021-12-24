FROM alpine:3.14
WORKDIR /app

RUN apk add --no-cache --update nmap-ncat

COPY hello.sh .
RUN chmod +x hello.sh
