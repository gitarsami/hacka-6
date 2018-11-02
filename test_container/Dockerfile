FROM alpine:3.8
MAINTAINER Sami Arpiainen
RUN apk update && apk upgrade
RUN apk add python pip
RUN pip install redis
RUN tail -f /dev/null &
