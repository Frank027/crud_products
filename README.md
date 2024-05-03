# CRUD_PRODUCTOS
El proyecto realiza las principales operaciones CRUD (Crear, Leer, Actualizar y Eliminar) para productos. Además, cuenta con un sistema de sesión implementado utilizando Jasonwebtoken para la autenticación de usuarios.
## Tabla de Contenidos

- [Descripción](#descripción)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Uso](#uso)
- [Contribución](#contribución)
- [Licencia](#licencia)

## Descripción
Sistema para la administración de un inventario de productos. Permite realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar) de manera eficiente, gestionando el inventario de manera integral y facilitando el seguimiento y control de los productos disponibles.

## Tecnologías Utilizadas
[![](https://skillicons.dev/icons?i=nodejs,express,mysql,pug,html,css,js)](https://skillicons.dev)
- Node.js
- Express.js
- MySQL
- Pug (motor de plantillas)
- HTML
- CSS
- JavaScript

## Instalación

1. Clona este repositorio.
2. Instala las dependencias usando npm:

   ```bash
   npm install

3. Configura la base de datos MySQL según las especificaciones del archivo `database.sql`.
4. Crea un archivo `.env` en la raíz del proyecto y configura las variables de entorno necesarias, como las credenciales de la base de datos y el secreto para Jasonwebtoken.
5. Inicia el servidor:


## Uso

Descripción sobre cómo utilizar el proyecto y las principales funcionalidades.
### Inicio de sesión
Este módulo tiene como proposito que el usurio se identifique, de forma que si es un usuario del sistema se le permita el acceso y a su vez se le cree un token de JsonWebToken que contendra su información y que le permitirá mantener su sesión abierta y pueda utilizar la funciones que el sistema ofrece.
### Gestión de productos
Para la gestión de productos, se implementan las principales funciones CRUD de las bases de datos. Cada una de estas funciones cuenta con un endpoint/ruta correspondiente y los métodos necesarios para su utilización.

## Contribución

Si deseas contribuir a este proyecto, sigue estos pasos:

1. Haz un fork del proyecto.
2. Crea una nueva rama (`git checkout -b feature/nueva-caracteristica`).
3. Haz tus cambios y haz commit de ellos (`git commit -am 'Agrega nueva característica'`).
4. Sube tus cambios (`git push origin feature/nueva-caracteristica`).
5. Abre un Pull Request.

## Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE).
