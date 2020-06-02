# Ansible role to install NGINX with PHP-FPM.

[![Build Status](https://travis-ci.org/andriusdj/ansible-nginx_php-fpm.svg?branch=master)](https://travis-ci.org/andriusdj/ansible-nginx_php-fpm)

## Dependencies

Debian-Based distribution

## Variables

Variable          | Description
----------------- | ---------------------------------------------------------------------------------
`php_packages`    | A list of Packages (e.g. `php-gd`) to be installed.
`tunables`        | A list of tunables to be adjusted in /etc/php/fpm/php.ini

