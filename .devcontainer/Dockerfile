FROM --platform="linux/amd64" mcr.microsoft.com/devcontainers/php:1-8.2-bullseye

RUN sudo apt update;sudo apt upgrade -y
RUN sudo pecl install -D 'enable-sockets="no" enable-openssl="yes" enable-http2="yes" enable-mysqlnd="yes" enable-hook-curl="yes" enable-cares="yes" with-postgres="no"' openswoole
COPY php.ini /usr/local/etc/php/php.ini