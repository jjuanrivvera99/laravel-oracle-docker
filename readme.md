<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

# Description

[This](https://github.com/jjuanrivvera99/laravel-oracle-docker) is a laravel project v5.8 that can connect to ORACLE databases through the oracle client and 'yajra/laravel-oci8' package. It also has a 'docker-compose.yml' file with which the application can be run with Docker.

## How to run this project

To run this project you need to have docker and docker-compose installed in your machine.

Take the following steps:

- clone this repository by executing the following command: 'git clone https://github.com/jjuanrivvera99/laravel-oracle-docker'
- change directory: 'cd laravel-oracle-docker'
- run command: 'docker-compose up -d'
- run command: 'docker exec -it laravel-oracle bash'
- run command: 'composer install'
- create a '.env' file
- run command: 'php atisan key:generate'
- run command: 'sudo chmod 777 -R storage' *
- run command: 'sudo chmod 777 -R bootstrap' *
- run command: 'sudo chmod 777 -R public' *

Optionally commnads

- php artisan config:cache
- php artisan migrate

*Only if you are using OS X or GNU/Linux (If you are using Windows, make sure that these folders have write permissions)

## License

The Laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
