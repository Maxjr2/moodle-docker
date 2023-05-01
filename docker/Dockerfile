FROM php:8.1-apache

RUN pecl install iconv \
    && pecl install mbstring \
    && pecl install curl \
    && pecl install openssl \
    && pecl install tokenizer \
    && pecl install xmlrpc \
    && pecl install soap \
    && pecl install ctype \
    && pecl install zip \
    && pecl install gd \
    && pecl install simplexml \
    && pecl install spl \
    && pecl install pcre \
    && pecl install dom \
    && pecl install xml \
    && pecl install intl \
    && pecl install json \
    && docker-php-ext-enable iconv mbstring curl openssl tokenizer xmlrpc soap ctype zip gd simplexml spl pcre dom xml intl json