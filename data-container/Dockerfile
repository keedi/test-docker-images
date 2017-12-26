FROM busybox:latest
MAINTAINER Keedi Kim <keedi.k@gmail.com>

RUN set -ex; \
    \
    mkdir -p /var/lib/mysql; \
    mkdir -p /var/www/html;

VOLUME [ "/var/lib/mysql", "/var/www/html" ]
