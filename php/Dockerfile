FROM php:7-apache
COPY php.ini /usr/local/etc/php/
RUN docker-php-ext-install mysqli mbstring \
  && a2enmod rewrite
