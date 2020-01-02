FROM alpine:3.11

LABEL maintainer "djjordaan@gmail.com"

RUN apk --no-cache add dnsmasq

VOLUME /etc/dnsmasq

EXPOSE 53 53/udp

ENTRYPOINT ["dnsmasq", "-k"]
