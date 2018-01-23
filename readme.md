<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Introduction
ขอขอบคุณ jayminpanchal/laravel-multiauth เป็น multiauth แยกกันระหว่าง User&Admin อย่างชัดเจน *สำหรับผู้เริ่มต้น

## Installation

1. Run `composer update` 
2. Run `chmod -R 777 storage` and `bootstrap/cache`
3. Create File `.env` or copy `.env.example` and rewite database connect.
4. Run `php artisan migrate` if you not copy file `.env` you can Configuration file `config/database.php` with database connect.
5. Run `php artisan key:generate`
6. `php artisan serv` Install successfully.



## License
The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
