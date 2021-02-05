FROM php:7.4-fpm-buster

RUN apt-get update && apt-get install -y \
    git \
    zlib1g-dev \
    libxml2-dev \
    libzip-dev \
    && docker-php-ext-install \
    zip \
    intl \
    mysqli \
    pdo pdo_mysql

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
COPY symfony/ /var/www/symfony
WORKDIR /var/www/symfony