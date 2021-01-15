# Laravel Blog

A simple blog for Laravel Final Exam

## login info

user: anzo@gmail.com | password: password


## Installation

```
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan db:seed
```

If you want dummy data, then run this-

```
php artisan db:seed --class=DummyDataSeeder
```
##