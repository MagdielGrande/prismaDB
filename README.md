# Prisma DB
Api: Express + DB

### Configuración
1. Crear un nuevo proyecto de js

2. Instalamos las siguientes dependecias al proyecto
    ```npm install express --save-dev```
    ```npm install prisma --save-dev```
    - prisma nos va ayudar a conectarnos a la base de datos en postgresql.

3. Iniciamos prisma con el comando ```npx prisma init```
    - Npx es una herramienta de cli que nos permite ejecutar paquetes de npm de forma mucho más sencilla.
4. Creamos la base de datos en postgresql. 
5. En el archivo ***.env*** modificalo con tu usuario y contraseña.
6. En el archivo ***prisma/schema.prisma*** creamos nuestros modelos.
7. Ejecutamos el siguiente comando ***```npx prisma migrate dev --name init```*** 
    - Este comando hace un _migrations_ que es como los commit en Git.


______________________________________________________________________________________________________________________

>El archivo seed.js contiene unos registros que se agregana la base de datos al ejecutar el script.
>El archivo server.js contiene la configuración para correr el servidor con el CRUD agregado.


