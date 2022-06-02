FROM php:8.1-fpm

RUN apt-get update && apt-get install -y \
        curl \
        unzip \
        npm \
        nodejs \
        libpq-dev \
    && docker-php-ext-install -j$(nproc) pdo pdo_pgsql

RUN curl -sS https://getcomposer.org/installer | php && mv composer.phar /usr/local/bin/composer

WORKDIR /var/www/html
