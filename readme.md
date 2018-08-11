<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

## Intro

- This repo contains a default Laravel 5.6 installation initialized to work with a MongoDB backend.
- The mongodb driver used is [jenssegers/mongodb](https://github.com/jenssegers/laravel-mongodb).
- The `.env` uses the **Connection String** (DB_DSN) format to connect to the mongodb server.
- Make sure `php_mongo` extension is installed and enabled in your environment.

## Usage

- Clone the repo first.
```
$ git clone https://github.com/amodsachintha/laravel-5.6-mongodb-starter
```
- `cd` into the directory and run the following `artisan` command.
```
$ php artisan key:generate
```
This will generate an new application key.
- Note tht this laravel application already has the authentication scaffolding added to it. In the event you want to remove it, do so manually.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
