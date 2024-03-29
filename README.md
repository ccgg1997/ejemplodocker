#Proyectos del Curso de Docker en Platzi
Este repositorio contiene una colección de proyectos utilizados como ejercicios prácticos en el curso de Docker en Platzi: https://platzi.com/. Cada carpeta dentro de este repositorio representa un proyecto individual relacionado con la utilización de Docker.

Descripción
Este repositorio ha sido creado como parte del curso de Docker en Platzi. Cada proyecto ha sido diseñado para explorar diferentes aspectos de la utilización de Docker en el desarrollo y despliegue de aplicaciones.

#Proyectos
1. API Python Flask:

Esta API está desarrollada con Flask y Python.
El puerto por defecto para ejecutar el contenedor es 5000.
Puedes modificar el puerto dentro del archivo app.py si lo deseas.
2. Página Web:

Esta página web está desarrollada con HTML, CSS y JavaScript.
El contenedor debe ser ejecutado en el puerto 80 para que la página web funcione correctamente.
Uso
Para cada proyecto:

#Clona este repositorio en tu máquina local:
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

#Ejecuta el contenedor utilizando el comando docker run:
API Python Flask:

Bash
docker run -it --rm -d -p 5000:5000 nombre-repo
Use code with caution.
Página Web:

Bash
docker run -it --rm -d -p 80:80 nombre-repo
Use code with caution.
Contribuciones
Siéntete libre de contribuir con mejoras, correcciones de errores o nuevos proyectos siguiendo los lineamientos de contribución.

Licencia
Este repositorio está licenciado bajo la licencia Apache 2.0.