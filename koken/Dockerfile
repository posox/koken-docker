FROM php:7.3-apache

## install image processor
RUN apt-get update && apt-get install -y graphicsmagick

## install php-mysql-extension
RUN docker-php-ext-install mysqli
