FROM alpine
MAINTAINER Keith Sharp <keith.sharp@passback.co.uk>

RUN apk add --no-cache python && \
    python -m ensurepip && \
    rm -r /usr/lib/python*/ensurepip && \
    pip install --upgrade pip setuptools && \
    rm -r /root/.cache

CMD /bin/sh
