FROM alpine:3.5
RUN apk add --update curl
RUN curl -o packer.zip  https://releases.hashicorp.com/packer/1.0.0/packer_1.0.0_linux_amd64.zip
RUN unzip packer.zip

FROM scratch
COPY --from=0 /packer /packer
ADD tmp /tmp
CMD ["/packer"]
