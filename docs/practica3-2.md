Natividad Márquez Baena

# Práctica 3.2: Despliegue de aplicaciones con Node Express

1. Introducción
2. Instalación de Node.js y Express
3. Test y despliegue de una nueva aplicación

## Introducción

En esta práctica se pretende realizar un despliegue de aplicaciones Node.js sobre un servidor Node Express.
Para ello primero se instala Node.js y Express. Tras ello crear un archivo .js de prueba para comprobar que nuestro el despliegue funciona correctamente.
Luego, en lugar de acceder a `http://localhost:3000`, se accede a la  máquina local a `http://IP-maq-virtual:3000`, utilizando la IP concreta de la máquina virtual.

## Instalación de Node.js

Primeramente y antes de nada, se detendrá el servicio tomcat para poder realizar la práctica.

![alt text](image-10.png)

Depués de eso se instalará node.js

![alt text](image-1.png)

A continuación, se comprueba las versiones instaladas de NodeJS y NPM para verificar si las instalaciones han tenido éxito.

![alt text](image-2.png)

## Test de la primera aplicación y despliegue de una nueva aplicación

Clonamos un repositorio aportado para la práctica, donde obtenemos una aplicación de ejemplo para desplegar y realizar las comprobaciones.

![alt text](image-3.png)

Nos moveremos al directorio y se instalarán las librerías necesarias:

![alt text](image-4.png)

A continuacion iniciamos la aplicación:

![alt text](image-5.png)

Como puede observarse, obtenemos el siguiente error: `sh: 1: nodemon: not found`. Para solucionar dicho error se ejecutará el comando:

![alt text](image-6.png)

Una vez subsanado el error, se vuelve a tratar de inicializar la aplicación:

![alt text](image-7.png)

Finalmente, accedemos a la dirección `http://localhost:3000/`, donde obtendremos la aplicación desplegada:

![alt text](image-8.png)


