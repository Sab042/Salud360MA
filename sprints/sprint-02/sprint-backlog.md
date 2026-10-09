# Sprint #2

## Información General del Sprint
- **Sprint:** 2
- **Fecha de inicio:** 02 de Octubre, 2026
- **Fecha de fin:** 16 de Octubre, 2026
- **Objetivo del Sprint (Sprint Goal):** Implementar el módulo de administración de entidades médicas (Médicos, IPS y Consultorios) permitiendo la configuración de horarios de atención y sedes habilitadas.

---

## Historias de Usuario Seleccionadas (Sprint Scope)

| ID | Historia de Usuario | Puntos de Historia | Prioridad | Estado |
| :--- | :--- | :---: | :---: | :---: |
| **US-04** | Gestión de Perfil de Médicos (CRUD) | 5 | Alta | En Progreso |
| **US-05** | Gestión de IPS y Sedes | 3 | Media | Pendiente |

**Total de Puntos de Historia del Sprint:** 8 Puntos

---

## Desglose de Tareas Técnicas (Task Breakout)

### US-04: Gestión de Perfil de Médicos (CRUD) (5 Puntos)
- [ ] **TSK-401:** Crear la entidad `Medico` asociada a la entidad `Usuario` con campos de Tarjeta Profesional y Especialidad.
- [ ] **TSK-402:** Diseñar e implementar la tabla/modelo para los horarios de atención de médicos.
- [ ] **TSK-403:** Crear controladores API REST para el CRUD de Médicos (`GET`, `POST`, `PUT`, `DELETE`).
- [ ] **TSK-404:** Agregar validación para impedir la eliminación de médicos con citas agendadas activas.

### US-05: Gestión de IPS y Sedes (3 Puntos)
- [ ] **TSK-501:** Diseñar la entidad `IPS` y `Consultorio` con relación uno a muchos.
- [ ] **TSK-502:** Implementar los endpoints de creación y listado filtrado de sedes activas.
- [ ] **TSK-503:** Realizar pruebas de integración entre las entidades IPS, Consultorio y Médico.

---

## Definición de Hecho (Definition of Done - DoD)
Para considerar una Historia de Usuario como completada en este Sprint debe cumplir con:
1. El código fue subido a la rama correspondiente mediante un Pull Request.
2. Pasó revisión de código por al menos un compañero del equipo.
3. Se realizaron pruebas unitarias locales y funcionaron correctamente.
4. Cumple con todos los criterios de aceptación especificados en la Historia de Usuario.

---