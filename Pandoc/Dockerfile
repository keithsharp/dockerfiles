FROM fedora:26
MAINTAINER Keith Sharp <kms@passback.co.uk>

RUN dnf -y update && dnf -y install pandoc-pdf && dnf clean all
RUN mkdir /src
WORKDIR /src
