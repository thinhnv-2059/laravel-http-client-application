# About

Laravel 8 CRUD application using [HTTP Client](https://laravel.com/docs/8.x/http-client) and [{JSON} Placeholder](https://jsonplaceholder.typicode.com/) REST API data.

# Installing

## Clone The Repository

Clone the repository to your environment, using the following command:

```bash
https://github.com/lecano/laravel-http-client-application.git
```

## Install Dependencies & Setup

Once cloned, navigate to the project's root directory and run composer install to install dependencies.

```bash
composer install
```

Copy the example env file and make the required configuration changes in the .env file.

```bash
cp .env.example .env
```

Generate a new application key.

```bash
php artisan key:generate
```

## Run Webserver

Start the local development server.

```bash
php artisan serve
```

# Contributing

Please contribute using [GitHub Flow](https://guides.github.com/introduction/flow). Create a branch, add commits, and [open a pull request](https://github.com/lecano/laravel-http-client-application/compare).

# License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
