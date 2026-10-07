# Sprint Backlog - Sprint 1

## Información General del Sprint
- **Sprint:** 1
- **Fecha de inicio:** 19 de Septiembre, 2026
- **Fecha de fin:** 01 de Octubre, 2026
- **Objetivo del Sprint (Sprint Goal):** Implementar la arquitectura base de la aplicación y el módulo de autenticación y registro de usuarios para permitir el acceso seguro a la plataforma SALUD360.

---

## Historias de Usuario Seleccionadas (Sprint Scope)

| ID | Historia de Usuario | Puntos de Historia | Prioridad | Estado |
| :--- | :--- | :---: | :---: | :---: |
| **US-01** | Registro de usuario | 5 | Alta | En Progreso |
| **US-02** | Inicio de sesión | 3 | Alta | Pendiente |

**Total de Puntos de Historia del Sprint:** 8 Puntos

---

## Desglose de Tareas Técnicas (Task Breakout)

### US-01: Registro de usuario (5 Puntos)
- [x] **TSK-101:** Diseñar el modelo de datos / entidad `Usuario` en Java (Campos: ID, Nombre, Documento, Email, Password, Rol). *(Responsable: Dev 1 | Est.: 3 hrs)*
- [ ] **TSK-102:** Crear el endpoint POST `/api/v1/auth/register` en el controlador de usuarios. *(Responsable: Dev 1 | Est.: 4 hrs)*
- [ ] **TSK-103:** Validar que el correo electrónico no esté duplicado en la base de datos. *(Responsable: Dev 2 | Est.: 2 hrs)*
- [ ] **TSK-104:** Implementar la encriptación de contraseñas utilizando BCrypt antes de guardar en la base de datos. *(Responsable: Dev 2 | Est.: 3 hrs)*

### US-02: Inicio de sesión (3 Puntos)
- [ ] **TSK-201:** Crear el servicio de autenticación y verificación de credenciales (email y contraseña). *(Responsable: Dev 1 | Est.: 4 hrs)*
- [ ] **TSK-202:** Configurar la generación y validación de tokens JWT (JSON Web Tokens) para sesiones. *(Responsable: Dev 2 | Est.: 4 hrs)*
- [ ] **TSK-203:** Retornar las respuestas de error estructuradas ante credenciales inválidas (HTTP status 401). *(Responsable: Dev 1 | Est.: 2 hrs)*

---

## Definición de Hecho (Definition of Done - DoD)
Para considerar una Historia de Usuario como completada en este Sprint debe cumplir con:
1. El código fue subido a la rama correspondiente mediante un Pull Request.
2. Pasó revisión de código por al menos un compañero del equipo.
3. Se realizaron pruebas unitarias locales y funcionaron correctamente.
4. Cumple con todos los criterios de aceptación especificados en la Historia de Usuario.


# Sprint 2

## Informacion general del Sprint
- **Sprint:** 2
- **Fecha de inicio:** 02 de octubre, 2026
- **Fecha de fin:** 16 de octubre, 2026
- **Objetivo del Sprint (Sprint Goal)**: ** Implementar el módulo de administración de entidades médicas (Médicos, IPS y consultorios) permitiento la confirguración de horarios de atención y sedes habilitadas.

___

# Historias de Usuario Seleccionadas (Sprint Scope)

| ID | Historia de Usuario | Puntos de Historia | Prioridad | Estado |
| :--- | :--- | :---: | :---: | :---: |
| **US-04** | Gestión de Perfil de Médicos (CRUD) | 5 | Alta | Pendiente |
| **US-05** | Gestión de IPS y Sedes | 3 | Media | Pendiente |

**Total de Puntos de Historia del Sprint:** 8 Puntos

---

## Desglose de Tareas Técnicas (Task Breakout)

### US-04: Gestión de Perfil de Médicos (CRUD) (5 Puntos)
- [ ] **TSK-401:** Crear la entidad `Medico` asociada a la entidad `Usuario` con campos de Tarjeta Profesional y Especialidad. *(Responsable: Dev 1 | Est.: 3 hrs)*
- [ ] **TSK-402:** Diseñar e implementar la tabla/modelo para los horarios de atención de médicos. *(Responsable: Dev 1 | Est.: 3 hrs)*
- [ ] **TSK-403:** Crear controladores API REST para el CRUD de Médicos (`GET`, `POST`, `PUT`, `DELETE`). *(Responsable: Dev 2 | Est.: 4 hrs)*
- [ ] **TSK-404:** Agregar validación para impedir la eliminación de médicos con citas agendadas activas. *(Responsable: Dev 2 | Est.: 2 hrs)*

### US-05: Gestión de IPS y Sedes (3 Puntos)
- [ ] **TSK-501:** Diseñar la entidad `IPS` y `Consultorio` con relación uno a muchos. *(Responsable: Dev 1 | Est.: 3 hrs)*
- [ ] **TSK-502:** Implementar los endpoints de creación y listado filtrado de sedes activas. *(Responsable: Dev 2 | Est.: 3 hrs)*
- [ ] **TSK-503:** Realizar pruebas de integración entre las entidades IPS, Consultorio y Médico. *(Responsable: Dev 1 | Est.: 2 hrs)*

---
## Definición de Hecho (Definition of Done - DoD)
Para considerar una Historia de Usuario como completada en este Sprint debe cumplir con:
1. El código fue subido a la rama correspondiente mediante un Pull Request.
2. Pasó revisión de código por al menos un compañero del equipo.
3. Se realizaron pruebas unitarias locales y funcionaron correctamente.
4. Cumple con todos los criterios de aceptación especificados en la Historia de Usuario.

