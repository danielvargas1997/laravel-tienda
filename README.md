🛍️ Tienda Laravel - Proyecto Web
Tienda Laravel es una aplicación web creada con Laravel 12.x y Jetstream, pensada para ser un sistema base moderno con autenticación, componentes Livewire, y un stack preparado para escalabilidad.

📦 Stack Tecnológico
Laravel 12.x

Jetstream con Livewire

MySQL (servidor local con Laragon)

Tailwind CSS

Alpine.js

PHP 8.3

Composer 2.8.x

Node.js y NPM

Laravel Mix / Vite

🚀 Requisitos del sistema
PHP >= 8.2

MySQL >= 5.7 o MariaDB >= 10.2

Composer

Node.js y npm

Git

Laragon (opcional para entorno Windows)

Navegador actualizado

⚙️ Instalación del proyecto
Clona el repositorio

bash
Copiar
Editar
git clone https://github.com/tu_usuario/laravel-tienda.git
cd laravel-tienda
Instala dependencias PHP

bash
Copiar
Editar
composer install
Instala dependencias de frontend

bash
Copiar
Editar
npm install && npm run dev
Copia y configura el entorno

bash
Copiar
Editar
cp .env.example .env
Abre el archivo .env y ajusta la configuración de la base de datos:

env
Copiar
Editar
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=tienda
DB_USERNAME=root
DB_PASSWORD=124567
⚠️ Nota: Cambiar la contraseña del usuario root por seguridad si se va a desplegar en producción.

🔑 Generar clave de aplicación
bash
Copiar
Editar
php artisan key:generate
🔧 Migraciones y base de datos
Si la base de datos tienda no existe aún, créala manualmente desde phpMyAdmin o Workbench.

Luego corre las migraciones:

bash
Copiar
Editar
php artisan migrate
🧩 Jetstream y autenticación
Este proyecto utiliza Laravel Jetstream con Livewire, lo cual incluye:

Registro y login

Verificación de correo

Recuperación de contraseña

Gestión de sesiones

API tokens (con Laravel Sanctum)

Perfil de usuario

Equipos (opcional)

🌐 URL de desarrollo
Con Laragon:

arduino
Copiar
Editar
http://tienda.test
O con el servidor embebido de Laravel:

bash
Copiar
Editar
php artisan serve
✅ Comandos útiles
bash
Copiar
Editar
# Iniciar servidor local
php artisan serve

# Ver rutas registradas
php artisan route:list

# Compilar assets
npm run dev

# Ver errores en consola Laravel
php artisan log:clear
🔒 Seguridad
Actualmente se usa la contraseña por defecto del usuario root (124567) para MySQL.

IMPORTANTE: No usar este usuario en producción. Se recomienda crear un nuevo usuario con permisos específicos.

📂 Estructura inicial
pgsql
Copiar
Editar
.
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
├── routes/
├── storage/
├── tests/
├── .env
└── README.md
🙌 Créditos
Este proyecto fue creado por Daniel Alejandro Vargas Uzuriaga, con el objetivo de construir una base sólida y escalable para futuros desarrollos web en Laravel.
<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

- **[Vehikl](https://vehikl.com)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Redberry](https://redberry.international/laravel-development)**
- **[Active Logic](https://activelogic.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
