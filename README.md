Lab2-ds7 - Proyecto Laravel
Descripción

Este proyecto es una aplicación desarrollada con Laravel como parte de un laboratorio académico. Incluye configuración de base de datos, migraciones y un sistema básico de autenticación.

Requisitos
PHP >= 8.x
Composer
Node.js y npm
MySQL
WampServer o entorno similar
Instalación
1. Clonar o descargar el proyecto
git clone <repositorio>
cd Lab2-ds7
2. Instalar dependencias de PHP
composer install
3. Configurar variables de entorno

Copiar el archivo .env.example a .env y configurar:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=lab2_ds7
DB_USERNAME=root
DB_PASSWORD=
4. Generar clave de la aplicación
php artisan key:generate
5. Ejecutar migraciones
php artisan migrate
Instalación de frontend
npm install
npm run dev
Ejecución del proyecto
php artisan serve

Abrir en el navegador:

http://127.0.0.1:8000
Funcionalidades
Sistema de autenticación (login y registro)
Migraciones de base de datos
Configuración con MySQL
Rutas básicas en Laravel
Notas
Asegurarse de que el servidor MySQL esté activo
Verificar la configuración del archivo .env
En caso de errores de configuración, ejecutar:
php artisan config:clear
