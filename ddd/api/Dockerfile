FROM php:7.2-fpm
RUN pecl install xdebug \
    && docker-php-ext-enable xdebug
    
#FROM php:7.2-fpm
#RUN apt-get -y update \
#&& apt-get install -y libicu-dev \
#libxml2-dev
#RUN docker-php-ext-configure intl
#RUN docker-php-ext-install pdo pdo_mysql intl
#RUN pecl install xdebug \
#    && docker-php-ext-enable xdebug
#RUN pecl install redis && docker-php-ext-enable redis
