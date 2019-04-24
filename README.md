# Taxi-API

## Before You Begin

Before you begin we recommend you read about the basic building blocks that assemble a Laravel application:
* Laravel - Go through [Laravel Official Website](https://laravel.com/) and proceed to their [Documentation](https://laravel.com/docs/5.3/), which should help you understand Laravel better.
* Laravel Passport - Go through [Laravel Passport ](https://laravel.com/docs/5.3/passport) and get understand about it.
* MVC - Go through [WIKIPEDIA](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller) and get understand about it.

## Quick Local Setup

* `git clone https://github.com/doremi9/taxi-api.git`
* `cd taxi-api`
* `composer install`
* `php artisan key:generate`
* `cp .env.example .env`
* Create a database and inform *.env*
* Inform *.env* for email sends
* `php artisan migrate --seed` to create and populate tables
* `php artisan serve` to start the app on http://localhost:8000/