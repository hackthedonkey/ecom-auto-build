FROM php:7.3-fpm
RUN docker-php-ext-install mysqli

#install git
RUN apt-get update && \
    apt-get install -y git
#git clone ecom source code
RUN git clone https://github.com/hackthedonkey/learning-app-ecommerce.git /var/www/html


