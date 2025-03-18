# Laravel AdminLTE 3.0 Skeleton

Este proyecto es una aplicación Laravel que utiliza el paquete Laravel-AdminLTE 3.0 como base para la interfaz de usuario.

## Requisitos

- PHP >= 7.3
- Composer
- Node.js y NPM
- MySQL

## Instalación

1. Clona el repositorio:

    ```bash
    git clone https://github.com/SoftSisPro/laravel-adminlte3-skeleton.git project_name
    cd project_name
    ```
2. Copia el archivo `.env.example` a `.env` y configura tu base de datos y otras variables de entorno:

    ```bash
    cp .env.example .env
    ```

3. Instala las dependencias de PHP:

    ```bash
    composer install
    ```

4. Instala las dependencias de Node.js:

    ```bash
    npm install
    npm run dev # o use build si es el caso
    ```

5. Genera la clave de la aplicación:

    ```bash
    php artisan key:generate
    ```

6. Ejecuta las migraciones y los seeders:

    ```bash
    php artisan migrate --seed
    ```

7. Inicia el servidor de desarrollo:

    ```bash
    php artisan serve
    ```

## Uso

- Accede a la aplicación en tu navegador en `http://localhost:8000`.
- Accede con los siguientes datos
    - email: test@example.com
    - pass: password

## Créditos

- [Laravel](https://laravel.com/)
- [Laravel-AdminLTE](https://jeroennoten.github.io/Laravel-AdminLTE/)

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).
