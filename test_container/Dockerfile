FROM alpine:3.8
MAINTAINER Sami Arpiainen
RUN apk update && apk upgrade
RUN apk add python py-pip
RUN pip install redis
CMD ["tail", "-f", "/dev/null", "&"]
