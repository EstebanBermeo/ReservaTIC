# 📘 ReservaTIC – Sistema de reservas para laboratorios TIC

## 🧾 Descripción general

*ReservaTIC* simula el funcionamiento de un sistema de reservas para laboratorios TIC en una institución de eduación superior. El sistema permite representar gráficamente la interacción de dos tipos de usuarios: docentes y administradores, quienes pueden consultar disponibilidad, realizar reservas o gestionar los espacios.

El proyecto ha sido diseñado con una arquitectura en capas y desarrollado de manera colaborativa usando herramientas como Figma y GitHub Projects para el diseño, planificación y documentación.

---

## 🎯 Objetivo del proyecto

Diseñar un prototipo navegable que represente las funcionalidades clave de un sistema de reservas, permitiendo:
- Validar disponibilidad de laboratorios.
- Diferenciar accesos y funciones según el tipo de usuario.
- Simular flujos lógicos entre pantallas con base en requerimientos funcionales y no funcionales.
- Documentar todo el proceso de forma colaborativa.

---

## 👥 Integrantes y roles

| Nombre completo                          | Rol asignado                                  | Responsabilidades principales                                                                 |
|------------------------------------------|-----------------------------------------------|-----------------------------------------------------------------------------------------------|
| *Esteban Bermeo*                       | Coordinador general / Documentador            | Organización del proyecto, cronograma, bitácora, estructura del repositorio, revisión final. |
| *Kevin Alexander Velasco Ramos*        | Diseñador de interfaz (Figma)                 |identificación de actores, Creación de pantallas, navegación del prototipo, diseño visual moderno e institucional.       |
| *Christian Leonardo Suárez Ríos*       | Analista funcional y arquitectónico           | Requisitos, diseño de arquitectura en capas, documentación técnica.|

---

## 🛠 Herramientas utilizadas

- [Figma] – Prototipado visual e interfaces interactivas.
- [GitHub Projects] – Gestión de tareas (Kanban).
- [GitHub Wiki] – Bitácora de decisiones y actas de reunión.

---

# Sistema ReservaTIC - Prototipo Frontend

Este es un prototipo funcional del sistema **ReservaTIC**, diseñado para facilitar la reserva y gestión de laboratorios o salas TIC por parte de docentes y administradores.

🔗 **Accede al prototipo en línea:**  
[https://heartfelt-fairy-dc7108.netlify.app/](https://heartfelt-fairy-dc7108.netlify.app/)

---

## 🛠 Estructura del proyecto

El sistema está desarrollado en HTML y CSS (estático), alojado en [Netlify](https://www.netlify.com/), sin necesidad de backend ni base de datos.

### Archivos principales:

| Archivo                        | Descripción                                     |
|-------------------------------|-------------------------------------------------|
| `index.html`                  | Página de inicio de sesión                     |
| `docente.html`                | Vista inicial para docentes                    |
| `laboratorios.html`           | Vista de selección de laboratorios             |
| `horarios_labX.html`          | Disponibilidad horaria por laboratorio         |
| `admin_laboratorios.html`     | Gestión de laboratorios (admin)                |
| `admin_calendario.html`       | Vista de calendario de reservas (admin)        |
| `admin_bloqueo.html`          | Formulario para bloqueo de horarios (admin)    |
| `admin_editar_laboratorio.html`| Edición de datos de laboratorio (admin)       |
| `style.css`                   | Estilos generales del sistema                  |

---

## 👥 Usuarios de prueba (simulados)

| Usuario      | Contraseña | Redirección     |
|--------------|------------|-----------------|
| `admin`      | `1234`     | Vista administrador |
| `docente`    | `1234`     | Vista docente       |

---

## 📄 Notas

- Este es un **prototipo de navegación estática**. Las reservas y bloqueos no se guardan en un servidor.

---
