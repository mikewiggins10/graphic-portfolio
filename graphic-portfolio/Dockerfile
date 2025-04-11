FROM php:8.1-apache

# Enable Apache mod_rewrite if needed
RUN a2enmod rewrite

# Copy site files
COPY . /var/www/html/

# Set working directory
WORKDIR /var/www/html/

# Expose port 80 (default web port)
EXPOSE 80
