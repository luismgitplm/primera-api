# API REST con Laravel

API básica desarrollada con Laravel para la gestión de productos informáticos.

## Descripción

El proyecto parte de la estructura estándar que ofrece Laravel y añade los siguientes elementos:

- Modificación del modelo `User` para incluir el trait `HasApiTokens`, permitiendo la creación y gestión de tokens de autenticación.
- Creación del modelo `Producto`, que representa la tabla de productos informáticos en la base de datos.
- Definición de rutas de la API protegidas mediante el middleware `sanctum` para la validación de tokens.

## Autenticación

La API utiliza **Laravel Sanctum** para la autenticación basada en tokens, garantizando el acceso seguro a las operaciones CRUD.

## Tipo de API

- RESTful
- Sin vistas
- Acceso a base de datos mediante Eloquent ORM
