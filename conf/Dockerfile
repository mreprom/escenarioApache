FROM php:7.4-apache
RUN apt update && apt upgrade -y
RUN a2enmod authn_socache
RUN a2enmod auth_basic
RUN a2enmod auth_digest status info
RUN service apache2 restart

