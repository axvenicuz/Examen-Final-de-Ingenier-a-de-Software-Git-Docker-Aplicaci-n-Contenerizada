# Examen-Final-de-Ingenier-a-de-Software
# TP Final – Ingeniería

Este proyecto corresponde al Trabajo Final de la materia Ingeniería.
Consiste en una aplicación web mínima desarrollada en HTML, versionada con Git y contenerizada con Docker.

---

## Datos del alumno
- Nombre: Nicolás Pauwels
- dni 42540375

---

## Descripción del proyecto
La aplicación es una página web simple que muestra el nombre y legajo del alumno.
El objetivo del trabajo es demostrar el uso de:
- Proyecto local
- Git y control de versiones
- Docker y contenedores
- Publicación en repositorio remoto

---

## Estructura del proyecto
Ejecutar el contenedor
docker run -p 8080:80 tp-final
Acceder a la aplicación

Abrir un navegador web y entrar a:

http://localhost:8080

Git
Inicializar repositorio
git init

Comandos completos para ejecutar todo 
docker build -t tp-final .
docker run -p 8080:80 tp-final

