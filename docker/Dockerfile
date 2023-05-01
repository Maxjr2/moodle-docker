FROM php:8.1-fpm

RUN apt-get update -y && apt-get install -y curl && apt-get clean -y
RUN apt-get install -y libzip-dev libicu-dev libpng-dev libxml2-dev libonig-dev libcurl4-openssl-dev libssl-dev libxml2-dev libxml2-utils libxslt1-dev libxslt1.1 libxslt-dev libxslt1.1 libxslt1-dev
RUN docker-php-ext-install iconv
RUN docker-php-ext-install curl
RUN docker-php-ext-install openssl
RUN docker-php-ext-install tokenizer
RUN docker-php-ext-install xmlrpc
RUN docker-php-ext-install soap
RUN docker-php-ext-install ctype
RUN docker-php-ext-install zip
RUN docker-php-ext-install gd
RUN docker-php-ext-install simplexml
RUN docker-php-ext-install spl
RUN docker-php-ext-install pcre
RUN docker-php-ext-install dom
RUN docker-php-ext-install xml
RUN docker-php-ext-install intl
RUN docker-php-ext-install json

RUN docker-php-ext-enable iconv 
RUN docker-php-ext-enable mbstring
RUN docker-php-ext-enable curl
RUN docker-php-ext-enable openssl
RUN docker-php-ext-enable tokenizer
RUN docker-php-ext-enable xmlrpc
RUN docker-php-ext-enable soap
RUN docker-php-ext-enable ctype
RUN docker-php-ext-enable zip
RUN docker-php-ext-enable gd
RUN docker-php-ext-enable simplexml
RUN docker-php-ext-enable spl
RUN docker-php-ext-enable pcre
RUN docker-php-ext-enable dom
RUN docker-php-ext-enable xml
RUN docker-php-ext-enable intl
RUN docker-php-ext-enable json
