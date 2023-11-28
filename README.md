# Laravel-REST-API-Example
Commerce API

## How to use
1. Run `git clone https://github.com/durairaj-web/laravel-rest` to clone the repository.
2. Run `composer install` to install composer dependencies.
3. Copy `.env.example` to `.env` and edit the database credentials there.
4. Run `php artisan key:generate` to generate an app encryption key.
5. Run `php artisan migrate --seed` to migrate the database.


## Available routes
- /register - It will create a new user and generate user session
- /login - It will retrun the user data and generate user session
- /logout - remove user session
- /public/products - product list

## Admin routes
- /public/orders - order list
- /admin/orders - order list
- /admin/products - product list
- /admin/users - user list
