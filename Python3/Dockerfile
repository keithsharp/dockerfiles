FROM alpine
MAINTAINER Keith Sharp <keith.sharp@passback.co.uk>

RUN apk add --update gettext gcc python3-dev musl-dev libffi-dev openssl-dev && rm -rf /var/cache/apk/*

RUN python3 -m ensurepip && rm -r /usr/lib/python*/ensurepip

CMD /bin/sh
