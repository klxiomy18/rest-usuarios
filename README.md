# API de Gestión de Usuarios

## Descripción
Esta API permite gestionar usuarios en un entorno de arquitectura cliente-servidor. Proporciona operaciones básicas de CRUD (Crear, Leer, Actualizar, Eliminar) para administrar la información de los usuarios, incluyendo validaciones de datos y autenticación de contraseñas.

## Características
- **Crear Usuarios**: Permite registrar nuevos usuarios con validaciones.
- **Leer Usuarios**: Consulta la lista de usuarios registrados.
- **Actualizar Usuarios**: Modifica la información de los usuarios existentes.
- **Eliminar Usuarios**: Desactiva usuarios en el sistema.
- **Validaciones**: Implementa validaciones para garantizar la integridad de los datos.

## Tecnologías Utilizadas
- **Node.js**: Entorno de ejecución de JavaScript en el servidor.
- **Express.js**: Framework para construir aplicaciones web y APIs.
- **MongoDB**: Base de datos NoSQL para almacenar información de usuarios.
- **Mongoose**: ODM para MongoDB en Node.js.
- **Express Validator**: Middleware para validar y sanitizar datos de entrada.
- **Bcrypt.js**: Librería para encriptar contraseñas.

## Instalación

### Prerequisitos
- Node.js (versión >= 14.x)
- MongoDB (local o en la nube)

### Pasos para la instalación
1. Intalar las dependencias con el comando ```npm install```
2. Configura las variables de entorno: Crea un archivo .env en la raíz del proyecto y agrega tus configuraciones
3. Inicia la aplicación con el comando ```npm start```