# Documentación de Arquitectura - Sistema ReservaTIC

## 🧠 Justificación de Patrones de Diseño Usados

### 🎯 Patrón MVC (Modelo - Vista - Controlador)

Aunque no hay backend implementado, el sistema simula una separación por responsabilidades alineada al patrón MVC:

- **Modelo**: Entidades como Usuario, Reserva, Laboratorio (simuladas en HTML)
- **Vista**: Archivos como `index.html`, `docente.html`, `admin_laboratorios.html`
- **Controlador**: Flujo de navegación y decisiones embebidas o futuras en JS

---

### 🏗️ Patrón de Arquitectura en Capas

Se reconocen tres capas lógicas en la estructura:

- **Presentación**: Interfaz de usuario (HTML)
- **Lógica simulada**: Validaciones de flujo mediante navegación
- **Datos embebidos**: Información estructurada fija (nombre de laboratorios, horarios)

---

### 📦 Patrón de Modularidad

Cada pantalla o funcionalidad está encapsulada en un archivo específico:

- `admin_calendario.html`, `admin_bloqueo.html`, `admin_editar_laboratorio.html`, etc.
- Esto facilita la mantenibilidad y escalabilidad del sistema

---

### ⚡ Patrón de Prototipado Rápido

El sistema fue diseñado como un prototipo funcional de baja complejidad:

- Frontend desplegado en **Netlify**
- Simulación completa sin lógica backend
- Ideal para validación de usabilidad, flujo y diseño antes de codificar

---
