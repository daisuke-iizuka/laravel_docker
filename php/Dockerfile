FROM php:7.4-fpm-alpine

RUN apk add autoconf build-base
RUN docker-php-ext-install pdo pdo_mysql
RUN pecl install xdebug \
  && docker-php-ext-enable xdebug
