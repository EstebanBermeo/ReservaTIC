# Arquitectura en Capas – Proyecto ReservaTIC

## 1. Introducción

El sistema **ReservaTIC**, cuyo objetivo es facilitar la gestión de reservas de laboratorios TIC, ha sido diseñado bajo el enfoque de **arquitectura en capas**. La organización en capas permite representar de forma lógica y estructurada los distintos componentes del sistema, facilitando su comprensión, mantenimiento y posible implementación futura.

---

## 2. ¿Qué es la arquitectura en capas?

La **arquitectura en capas** es un modelo estructural que divide el sistema en distintos niveles, donde cada capa tiene responsabilidades específicas y se comunica únicamente con la capa inmediatamente superior o inferior. Esta separación promueve la modularidad, reutilización y escalabilidad del sistema.

---

## 3. Capas definidas para ReservaTIC

A continuación, se describen las tres capas adoptadas para el prototipo de ReservaTIC:

### 🔹 1. Capa de Presentación (Frontend)

- **Responsable:** Kevin
- Representa la interfaz gráfica del usuario, diseñada completamente en **Figma**.
- Incluye pantallas para el login, visualización de horarios, reservas, panel administrativo, entre otros.
- Su objetivo es ofrecer una experiencia intuitiva y visualmente clara tanto para docentes como administradores.
- Esta capa simula la interacción directa del usuario con el sistema.

### 🔹 2. Capa de Lógica de Negocio

- **Responsable:** Christian
- Aunque no se implementa programación, esta capa se representa mediante el **flujo lógico entre pantallas** y las decisiones que debería tomar el sistema.
- Define las reglas y condiciones del sistema, como:
  - Validación de horarios disponibles.
  - Bloquear horarios para mantenimiento u otras razones.
  - Acceso diferenciado según el rol (docente/administrador).
- Esta capa se explica en los documentos de requisitos y funcionalidades.

### 🔹 3. Capa de Datos

- **Responsable:** Christian
- Simula la gestión de la información (usuarios, laboratorios, horarios, reservas).
- No se utilizará una base de datos real, pero los datos estarán representados visualmente en tablas o pantallas dentro del prototipo (por ejemplo, calendarios con estados: disponible/ocupado/bloqueado).

---

## 4. Justificación del uso de esta arquitectura

Se optó por la arquitectura en capas debido a:

- ✅ Su **claridad estructural**, que permite dividir el proyecto en componentes manejables por cada integrante.
- ✅ Su **flexibilidad**, ya que el prototipo puede evolucionar a una versión funcional con código real.
- ✅ Su **correspondencia natural con herramientas como Figma**, donde cada pantalla representa la capa de presentación y el flujo de navegación representa parte de la lógica de negocio.
- ✅ Su **adecuación para proyectos colaborativos**, permitiendo asignar tareas a distintos roles sin interferencias.

---

## 5. Diagrama conceptual

            ┌──────────────────────────────┐
            │      Usuario final           │
            └────────────┬─────────────────┘
                         │
                         ▼
            ┌──────────────────────────────┐
            │   Capa de Presentación        │
            │ (Diseño en Figma)             │
            └────────────┬─────────────────┘
                         ▼
            ┌──────────────────────────────┐
            │   Capa de Lógica de Negocio   │
            │ (Reglas y flujo entre pantallas)│
            └────────────┬─────────────────┘
                         ▼
            ┌──────────────────────────────┐
            │        Capa de Datos          │
            │ (Representación visual de     │
            │ usuarios, horarios, reservas) │
            └──────────────────────────────┘

---

**Fecha de elaboración:** Abril 2025  
**Integrantes del equipo:**  
- Esteban (coordinación y documentación)  
- Kevin (diseño de interfaces)  
- Christian (análisis funcional y arquitectura)

