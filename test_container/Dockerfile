FROM alpine:3.8
MAINTAINER Sami Arpiainen
RUN apk update && apk upgrade
RUN apk add python
RUN pip install redis
RUN tail -f /dev/null &
