# Use the official PHP image with Apache
FROM php:8.1-apache

# Copy the source code into the container
COPY . /var/www/html/

# Enable Apache mod_rewrite
RUN a2enmod rewrite

# Install any additional PHP extensions you need here
# For example, install mysqli
RUN docker-php-ext-install mysqli
