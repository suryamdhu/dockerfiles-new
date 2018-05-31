FROM php:7.0-apache
RUN apt-get update && \
apt-get insatll -y php-mysql && \
apt-get clean


#Step to inject the latest code.

COPY myapp /var/www/html
