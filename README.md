<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Test Laravel - Login User - Register User + Boostrap

## Requisitos

- PHP 8.2.4v
- Composer 2.6.5v
- Laravel 5.1.3v

## Instalación

1. Clona este repositorio en tu máquina local:

   git clone https://github.com/MarinaDevops4/testProjects.git
2. Accede al directorio del proyecto
   cd testProjects-laraveltest

3. Instala las dependencias del proyecto Composer:
    composer install
   
4. Copia el archivo .env.example a .env y configura las variables de entorno, como la conexión a la base de datos y la clave de cifrado.
   cp .env.example .env
   
5. Genera una nueva clave de aplicación:
   php artisan key:generate
   
6. Ejecuta las migraciones para configurar la base de datos:
   php artisan migrate
   
7. Ejecuta el comando para compilar los recursos font-end
   npm install
   npm run dev

8. Inicia el servidor de desarrollo de Laravel
   php artisan serve

9. Abre tu navegador y entra en http://localhost:8000 para ver la aplicación

