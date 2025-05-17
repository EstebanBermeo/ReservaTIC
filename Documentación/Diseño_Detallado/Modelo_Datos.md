# Documentación de Arquitectura - Sistema ReservaTIC

## 📌 Modelo de Datos (simulado)

Aunque el sistema actual es un prototipo estático (frontend HTML/CSS en Netlify), se plantea un modelo lógico de datos para una futura implementación funcional.

### Entidades principales

| Entidad       | Atributos principales                                                                 |
|---------------|----------------------------------------------------------------------------------------|
| **Usuario**   | `id`, `nombre`, `rol` (docente/admin), `contraseña`                                   |
| **Laboratorio** | `id`, `nombre`, `ubicacion`, `capacidad`                                            |
| **Reserva**   | `id`, `fecha`, `horaInicio`, `horaFin`, `motivo`, `usuarioId`, `laboratorioId`        |
| **Bloqueo**   | `id`, `fecha`, `horaInicio`, `horaFin`, `motivo`, `laboratorioId`                     |

### Relaciones

- Un **usuario** puede realizar múltiples **reservas**
- Un **laboratorio** puede tener múltiples **reservas** y **bloqueos**
- Una **reserva** está vinculada a un único **usuario** y un único **laboratorio**

---
