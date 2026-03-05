Sistema de Gestión de Biblioteca
Universidad Don Bosco – Ciclo 01/2026

Materia: Diseño y Programación de Software Multiplataforma
Docente: Ing. Bladimir Díaz Campos

🧩 1. Descripción General

El presente proyecto consiste en el modelamiento y diseño de una base de datos para la gestión de la Biblioteca de la Universidad Don Bosco.

El sistema tiene como propósito estructurar y organizar la información relacionada con:

Libros

Estudiantes

Bibliotecarios

Préstamos y devoluciones

El diseño busca reducir redundancia, mejorar la integridad de datos y facilitar la consulta eficiente de información.

🎯 2. Objetivos del Proyecto
Objetivo General

Diseñar una base de datos estructurada que permita gestionar de forma eficiente los recursos bibliográficos de la biblioteca universitaria.

Objetivos Específicos

Identificar usuarios y roles del sistema.

Definir entidades y relaciones.

Establecer restricciones de integridad.

3. Actores del Sistema
| Rol           | Descripción                          |
| ------------- | ------------------------------------ |
| Administrador | Acceso total al sistema              |
| Bibliotecario | Registro de préstamos y devoluciones |
| Estudiante    | Consulta y solicitud de libros       |

⚙️ 4. Tecnologías Utilizadas
🔹 Frontend

React (Arquitectura basada en componentes)

Context API (Gestión de autenticación)

React Router (Enrutamiento)

🔹 Backend

PHP

Servidor Apache

🔹 Base de Datos

SQL Server

🔹 Herramientas de Desarrollo

Git

GitHub

Visual Studio Code

🏗 5. Arquitectura del Software

El sistema está diseñado bajo una arquitectura cliente-servidor:

Frontend (React)
⬇
Backend (PHP – API REST)
⬇
Base de Datos (SQL Server)

## Estructura de Componentes
src/
 ├── components/
 ├── context/
 ├── services/
 ├── pages/
 ├── App.jsx

 Gestión del Estado

Context API para autenticación.

Estados locales para formularios.

Manejo de sesión de usuarios.

Enrutamiento

React Router para navegación sin recarga.

🗄 6. Modelo de Base de Datos
Entidades Principales

Libro

Estudiante

Bibliotecario

Préstamo

Editorial

Categoría

Restricciones

Código de libro único.

Carnet de estudiante único.

Un libro solo puede tener un estado a la vez.

No se permite préstamo si el libro no está disponible.

📌 7. Requisitos del Sistema
Funcionales

Registro de libros.

Registro de estudiantes.

Registro de préstamos.

Control de devoluciones.

Búsqueda por código, autor o título.

No Funcionales

Integridad de datos.

Seguridad de acceso.

Rapidez en consultas.

Control de estados.

Alcance del Proyecto

El sistema permite:

Registro y gestión de libros.

Control de préstamos y devoluciones.

Consulta de disponibilidad.

Limitaciones

Diseño preliminar (no implementado completamente).

No incluye sistema en línea en esta fase.

Sujeto a mejoras en fases posteriores.

👨‍💻 10. Equipo de Desarrollo

Argueta Portillo Ángel Vladimir

Centeno Ramos Alisson Michelle

Centeno Ramos Brandon de Jesús

Fuentes Arriaza Meylin Gissell

📅 Fecha de Entrega

05 de marzo de 2026

Diseñar un modelo preliminar de base de datos.

Proponer una arquitectura de software coherente.
