FROM php:7.3.2-apache

COPY . /var/www/html

RUN apt-get update
RUN apt-get upgrade -y
EXPOSE 80
RUN echo 'ServerName localhost' >> /etc/apache2/apache2.conf
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]

