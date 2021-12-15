# BTC Blog 1

A simple Laravel blog that allows for posting articles, and creating pages.

## Requirements

* Composer
* PHP 8.0+

## Installation

```bash
cd btc-blog-1
composer install --no-dev OR composer update --ignore-platform-reqs
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
````

This will install the blog with an admin user with the following details. Currently these details can only be changed within the database.

email: `admin@example.com`<br>
password: `password`
