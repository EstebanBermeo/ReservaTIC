# Requisitos Funcionales y No Funcionales - ReservaTIC

## 1. Introducción

Este documento contiene los requisitos funcionales y no funcionales del sistema ReservaTIC. El objetivo es definir de manera precisa el comportamiento esperado del sistema desde la perspectiva de cada usuario según el rol.

---

## 2. Requisitos Funcionales (RF)

 A continuación se definen las acciones y operaciones que el sistema debe permitir a los usuarios. 

| Código | Requisito Funcional                                 | Descripción                                                                 |
|--------|------------------------------------------------------|-----------------------------------------------------------------------------|
| RF1    | Inicio de sesión por rol                             | El sistema debe permitir iniciar sesión como *docente* o *administrador*. |
| RF2    | Visualizar disponibilidad de laboratorios            | El docente debe poder consultar los horarios disponibles de los laboratorios TIC. |
| RF3    | Realizar una reserva                                 | El docente debe poder seleccionar fecha, hora y laboratorio disponible.     |
| RF4    | Confirmación visual de la reserva                    | El sistema debe mostrar una confirmación visual clara de la reserva realizada. |
| RF5    | Acceso al panel administrativo                       | El administrador debe tener acceso a un panel con la vista general de reservas. |
| RF6    | Gestión de laboratorios (crear, editar, eliminar)    | El administrador debe poder modificar los datos de los laboratorios disponibles. |
| RF7    | Bloqueo de horarios para mantenimiento u otras causas| El administrador debe poder marcar horarios como no disponibles.            |

---

## 3. Requisitos No Funcionales (RNF)

Los requisitos no funcionales establecen criterios que describen cómo debe comportarse el sistema, sin estar directamente relacionados con funcionalidades específicas.

| Código | Requisito No Funcional                             | Descripción                                                                 |
|--------|-----------------------------------------------------|-----------------------------------------------------------------------------|
| RNF1   | Navegación intuitiva                                | El prototipo debe tener un flujo lógico y comprensible entre pantallas.     |
| RNF2   | Compatibilidad visual                               | El diseño debe estar adaptado a pantallas de computadora y dispositivos móviles. |
| RNF3   | Diferenciación de roles                             | Las interfaces deben distinguir claramente entre usuarios docente y administrador. |
| RNF4   | Representación visual del estado de los laboratorios| Los estados (ocupado, libre, bloqueado) deben representarse con colores. |
| RNF5   | Accesibilidad básica                                | Las pantallas deben tener botones e iconografía clara, y textos legibles.   |
| RNF6   | Diseño institucional                                 | Se utilizarán colores institucionales (tonos azules) y estilo moderno-minimalista. |
| RNF7   | Documentación y trazabilidad del proyecto           | Toda la documentación debe estar organizada en el repositorio GitHub, incluyendo bitácoras y archivos fuente. |

---


*Fecha de elaboración:* Abril 2025
