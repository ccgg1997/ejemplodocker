# Proyectos del Curso de Docker en Platzi

Este repositorio contiene una colección de proyectos utilizados como ejercicios prácticos en el curso de Docker en Platzi: https://platzi.com/. Cada carpeta dentro de este repositorio representa un proyecto individual relacionado con la utilización de Docker.

## Descripción

Este repositorio ha sido creado como parte del curso de Docker en Platzi. Cada proyecto ha sido diseñado para explorar diferentes aspectos de la utilización de Docker en el desarrollo y despliegue de aplicaciones.

## Uso

Cada carpeta en este repositorio contiene un proyecto diferente. Para construir y ejecutar los proyectos con Docker, sigue estos pasos:

Clona este repositorio en tu máquina local:
Bash
git clone https://github.com/ccgg1997/ejemplodocker.git
Use code with caution.
Navega a la carpeta del proyecto que deseas utilizar:
Bash
cd proyectos-platzi/nombre-del-proyecto
Use code with caution.
Construye la imagen del contenedor utilizando el comando docker build:
Bash
docker build -t nombre-repo .
Use code with caution.
Reemplaza nombre-repo con el nombre que desees para la imagen del contenedor.

Ejecuta el contenedor utilizando el comando docker run:
Bash
docker run -it --rm -d -p 8080:80 nombre-repo
Use code with caution.
Este comando ejecutará el contenedor en segundo plano y mapeará el puerto 8080 del host al puerto 80 del contenedor.

## Contribuciones

Siéntete libre de contribuir con mejoras, correcciones de errores o nuevos proyectos siguiendo los lineamientos de contribución.

## Licencia

Este repositorio está licenciado bajo la licencia Apache 2.0.