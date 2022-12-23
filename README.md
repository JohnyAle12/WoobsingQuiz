<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## About Project

This is a web application where i put some knowledges, here i build a basic application where i created some models, middlewares, migations and relationships.

## Start Project

Before you download project, please run:

```bash
# install vendor packages
$ composer install
```

After configure your .env file according your database enviroment.

For generate the new application key

```bash
# generat new key aplication on the .env file
$ php artisan key:generate
```

Having the .env file you can excetue laravel migrations with:

```bash
# run laravel migation and create the data model
$ php artisan migrate
```

After that you can start the application in local with:

```bash
# start the virtual server and run application
$ php artisan serve
```
