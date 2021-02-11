FROM php:7.3-fpm

RUN docker-php-source extract \
    && docker-php-ext-install \
    pdo \
    mbstring \
    && docker-php-source delete

WORKDIR /var/www

ENTRYPOINT ["php-fpm", "-F", "-R"]