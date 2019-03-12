FROM php:7.1-fpm-alpine

# lumen packages
RUN docker-php-ext-install mbstring tokenizer mysqli pdo_mysql sockets gd intl opcache bcmath 
pecl channel-update pecl.php.net
pecl install mongodb
docker-php-ext-enable mongodb 
