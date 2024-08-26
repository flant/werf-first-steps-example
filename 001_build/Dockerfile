FROM alpine:3.20@sha256:0a4eaa0eecf5f8c050e5bba433f58c052be7587ee8af3e8b3910ef9ab5fbe9f5
WORKDIR /app

RUN apk add --no-cache --update nmap-ncat

COPY hello.sh .
RUN chmod +x hello.sh
