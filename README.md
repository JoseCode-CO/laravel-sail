<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Project

Ejemplo basico de como utilizar Laravel sail.

Laravel Sail es una herramienta incluida en el framework de Laravel que proporciona 
un entorno de desarrollo local ligero y rápido para proyectos Laravel. 
Sail está diseñado para facilitar la configuración y ejecución de aplicaciones
 Laravel en contenedores Docker.
 
 Al utilizar Laravel Sail, puedes crear rápidamente un entorno de desarrollo 
local consistente y reproducible para tu aplicación Laravel, sin la necesidad de configurar 
manualmente el entorno, las dependencias y los servicios relacionados.

Para crear un proyecto de laravel sail es necesario este comando:  curl -s "https://laravel.build/laravel-sail" | bash


Comandos basicos de laravel sail

./vendor/bin/sail up: Este comando inicia los contenedores Docker para tu proyecto Laravel. Inicia los servicios necesarios, como el servidor web, la base de datos y otros servicios configurados en tu entorno.

./vendor/bin/sail down: Este comando detiene y elimina los contenedores Docker asociados a tu proyecto Laravel. Utilízalo cuando desees detener el entorno de desarrollo local.

./vendor/bin/sail artisan: Puedes utilizar este comando para ejecutar los comandos Artisan de Laravel dentro del contenedor Docker. Por ejemplo, para ejecutar las migraciones de la base de datos: ./vendor/bin/sail artisan migrate.

./vendor/bin/sail shell: Este comando te permite acceder al shell del contenedor principal de Sail, lo que te brinda acceso a una terminal dentro del contenedor Docker. Puedes utilizar este comando para ejecutar comandos personalizados o interactuar con el entorno de desarrollo.

./vendor/bin/sail npm: Si tu proyecto utiliza npm para la gestión de paquetes JavaScript, puedes utilizar este comando para ejecutar comandos npm dentro del contenedor Docker. Por ejemplo, para instalar las dependencias JavaScript: ./vendor/bin/sail npm install.
