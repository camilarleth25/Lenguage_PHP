# Proyecto PHP con Docker

Este archivo proporciona las instrucciones necesarias para construir y ejecutar un proyecto PHP dentro de un contenedor Docker.

## Requisitos Necesarios

Asegúrate de tener Docker instalado en tu máquina antes de comenzar.

## Pasos para Ejecutar el Proyecto

### Paso 1: Crear la Imagen Docker

Navega a la carpeta `LENGUAGE-PHP`, abre una terminal y ejecuta el siguiente comando para generar la imagen Docker:

- docker build -t pagephp .

### Paso 2: Ejecutar el Contenedor Docker

Una vez que la imagen se haya creado correctamente, inicia el contenedor Docker y asigna el puerto 8080 de tu máquina al contenedor con el siguiente comando:

- docker run -p 8080:80 pagephp

