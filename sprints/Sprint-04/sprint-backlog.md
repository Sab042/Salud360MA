# Sprint Backlog - Sprint 4

## Información General del Sprint
- **Sprint:** 4
- **Fecha de inicio:** 01 de Noviembre, 2026
- **Fecha de fin:** 15 de Noviembre, 2026
- **Objetivo del Sprint (Sprint Goal):** Registrar y gestionar la atención en sala de espera (check-in) y construir los módulos clínicos de atención médica e historia clínica digital.

---

## Historias de Usuario Seleccionadas (Sprint Scope)

| ID | Historia de Usuario | Puntos de Historia | Prioridad | Estado |
| :--- | :--- | :---: | :---: | :---: |
| **US-08** | Consulta de Historia Clínica Digital | 5 | Alta | Pendiente |
| **US-09** | Registro de Atenciones por el Médico | 8 | Alta | Pendiente |
| **US-10** | Check-in y Registro de Visita | 3 | Media | Pendiente |

**Total de Puntos de Historia del Sprint:** 16 Puntos

---

## Desglose de Tareas Técnicas (Task Breakout)

### US-08: Consulta de Historia Clínica Digital (5 Puntos)
- [ ] **TSK-801:** Diseñar la consulta JPA con ordenamiento cronológico descendente por paciente.
- [ ] **TSK-802:** Aplicar filtros de seguridad para garantizar acceso exclusivo al paciente o médico asignado.
- [ ] **TSK-803:** Integrar librería para exportación de la historia clínica en formato PDF.

### US-09: Registro de Atenciones por el Médico (8 Puntos)
- [ ] **TSK-901:** Crear el modelo `HistoriaClinica` y `AtencionMedica` asociando códigos de diagnóstico CIE-10.
- [ ] **TSK-902:** Desarrollar el servicio REST para guardar la atención médica durante la consulta.
- [ ] **TSK-903:** Aplicar regla de inmutabilidad (bloqueo de edición) sobre registros clínicos guardados.

### US-10: Check-in y Registro de Visita (3 Puntos)
- [ ] **TSK-1001:** Crear el endpoint PUT `/api/v1/citas/{id}/checkin` para recepcionistas.
- [ ] **TSK-1002:** Actualizar estado de la cita a "En Sala de Espera" y notificar al panel del médico.

---

## Definición de Hecho (Definition of Done - DoD)
Para considerar una Historia de Usuario como completada en este Sprint debe cumplir con:
1. El código fue subido a la rama correspondiente mediante un Pull Request.
2. Pasó revisión de código por al menos un compañero del equipo.
3. Se realizaron pruebas unitarias locales y funcionaron correctamente.
4. Cumple con todos los criterios de aceptación especificados en la Historia de Usuario.

---