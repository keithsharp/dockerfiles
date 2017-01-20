FROM fedora:latest
MAINTAINER Keith Sharp <keith.sharp@passback.co.uk>

RUN dnf -y update && dnf clean all

RUN dnf -y install gcc-c++ clang cmake make && dnf clean all

CMD /usr/bin/bash
