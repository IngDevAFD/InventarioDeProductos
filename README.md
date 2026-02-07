MI INVENTARIO

Aplicación web desarrollada con Laravel para la gestión de inventario, permitiendo administrar productos y registrar movimientos de stock.

REQUISITOS

Antes de ejecutar el proyecto, asegúrate de tener instalado:

- PHP 8.2 o superior
- Composer
- Node.js y NPM
- Base de datos MySQL (o compatible)

CONFIGURACIÓN DEL ENTORNO

- Clona o descomprime el proyecto en tu equipo.
- Accede a la carpeta del proyecto:
  cd mi-inventario
- Copia el archivo de entorno:
  cp .env.example .env
- Configura en el archivo .env los datos de tu base de datos:
  DB_DATABASE=inventario_db
  DB_USERNAME=root
  DB_PASSWORD=

INSTALACIÓN DE DEPENDENCIAS

- Ejecuta los siguientes comandos:
  composer install
  npm install
- Genera la clave de la aplicación:
  php artisan key:generate

MIGRACIONES Y SEEDERS

- Ejecuta las migraciones para crear las tablas en la base de datos:
  php artisan migrate
- Puedes ejecutar los seeders con:
  php artisan db:seed
- (O ambos juntos):
  php artisan migrate --seed

EJECUCIÓN DEL PROYECTO

- Inicia el servidor de desarrollo:
  php artisan serve
- En otra terminal, compila los recursos frontend:
  npm run dev
- Luego accede desde el navegador a:
  http://localhost:8000

TECNOLOGÍAS UTILIZADAS

- Laravel 12
- PHP 8.2
- MySQL
- Vite
- Tailwind CSS

AUTOR

Andrés Duque
