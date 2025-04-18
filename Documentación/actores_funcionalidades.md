# Actores y Funcionalidades - ReservaTIC

## 1. Actores del sistema

El prototipo ReservaTIC contempla dos tipos de usuarios principales que interactúan con el sistema:

### 🧑‍🏫 Docente
Es el usuario que requiere reservar un laboratorio TIC para realizar una clase o actividad académica. Tiene acceso a consultar disponibilidad y generar reservas.

*Acciones permitidas:*
- Iniciar sesión como docente
- Consultar disponibilidad de laboratorios por fecha y hora
- Realizar una reserva en base a la disponibilidad

---

### 🧑‍💼 Administrador TIC
Es el responsable del control y gestión de los laboratorios TIC. Supervisa el uso de recursos, gestiona horarios y mantiene actualizado el sistema.

*Acciones permitidas:*
- Iniciar sesión como administrador
- Visualizar calendario completo de reservas
- Agregar, editar o eliminar laboratorios TIC
- Asignar o bloquear horarios para mantenimiento o uso especial

---

## 2. Funcionalidades principales del sistema

A continuación, se listan las funcionalidades que serán representadas en el prototipo funcional del sistema:

| Código | Funcionalidad                                      | Actor          | Descripción                                                                 |
|--------|----------------------------------------------------|----------------|-----------------------------------------------------------------------------|
| F1     | Iniciar sesión                                     | Docente / Admin | Permite ingresar al sistema según el rol previamente asignado              |
| F2     | Ver disponibilidad de laboratorios                 | Docente        | Consulta visual (por colores) de disponibilidad según día y hora            |
| F3     | Realizar una reserva                               | Docente        | Selecciona laboratorio, fecha y hora                                        |
| F4     | Acceder al panel administrativo                    | Administrador  | Muestra todas las reservas y opciones de gestión de laboratorios            |
| F5     | Agregar / eliminar / editar laboratorios           | Administrador  | Permite gestionar las salas TIC disponibles en el sistema                   |
| F6     | Bloquear horarios para mantenimiento u otras razones | Administrador  | Evita reservas en ciertos horarios al marcarlos como no disponibles       |

---

## 3. Interacción esperada

- El prototipo mostrará pantallas separadas para *docente* y *administrador* luego del login.
- Las funcionalidades estarán representadas con interfaces intuitivas, botones interactivos y navegación fluida.
- Los colores serán clave para diferenciar disponibilidad:  
  - *Verde*: Disponible  
  - *Rojo*: Ocupado  
  - *Gris*: No disponible (bloqueado)

---

*Fecha de elaboración: 17 de Abril 2025  
