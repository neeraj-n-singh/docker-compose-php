FROM php:8.3.6-fpm-alpine3.18

# Copy the php config file
COPY php/php-fpm.conf /usr/local/etc/php-fpm.d/www.conf

# Copy only the source code to /app
COPY src /app

VOLUME ["/app"]