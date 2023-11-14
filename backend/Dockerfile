# Use the official PHP image with Apache
FROM php:8.0-apache

# Install additional PHP extensions if needed
RUN docker-php-ext-install mysqli pdo pdo_mysql

# Copy the PHP source code into the container
COPY . /var/www/html

# Expose port 80
EXPOSE 80
