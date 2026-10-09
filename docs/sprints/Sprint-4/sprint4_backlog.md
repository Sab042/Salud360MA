# Sprint Backlog - Sprint 4

## Información General del Sprint
- **Sprint:** 4
- **Fecha de inicio:** 01 de Noviembre, 2026
- **Fecha de fin:** 15 de Noviembre, 2026
- **Objetivo del Sprint (Sprint Goal):** Completar el módulo clínico con el registro inmutable de la atención médica, la consulta de historias clínicas y el despacho de medicamentos.

---

## Historias de Usuario Seleccionadas (Sprint Scope)

| ID | Historia de Usuario | Puntos de Historia | Prioridad | Estado |
| :--- | :--- | :---: | :---: | :---: |
| **US-08** | Consulta de Historia Clínica Digital | 5 | Alta | Pendiente |
| **US-09** | Registro de Atenciones por el Médico | 8 | Alta | Pendiente |
| **US-11** | Formulación y Solicitud de Medicamentos | 5 | Media | Pendiente |

**Total de Puntos de Historia del Sprint:** 18 Puntos

---

## Desglose de Tareas Técnicas (Task Breakout)

### US-08: Consulta de Historia Clínica Digital (5 Puntos)
- [ ] **TSK-801:** Diseñar la consulta SQL / JPA con ordenamiento cronológico descendente por paciente. (Responsable: Dev 1 | Est.: 3 hrs)
- [ ] **TSK-802:** Aplicar filtros de seguridad para garantizar acceso exclusivo al paciente o médico asignado. (Responsable: Dev 2 | Est.: 3 hrs)
- [ ] **TSK-803:** Integrar librería para exportación de la historia clínica en formato PDF. (Responsable: Dev 1 | Est.: 4 hrs)

### US-09: Registro de Atenciones por el Médico (8 Puntos)
- [ ] **TSK-901:** Crear el modelo HistoriaClinica y AtencionMedica asociando códigos de diagnóstico CIE-10. (Responsable: Dev 1 | Est.: 4 hrs)
- [ ] **TSK-902:** Desarrollar el servicio REST para guardar la atención médica durante la consulta. (Responsable: Dev 2 | Est.: 5 hrs)
- [ ] **TSK-903:** Aplicar regla de inmutabilidad (bloqueo de edición) sobre registros clínicos guardados. (Responsable: Dev 2 | Est.: 3 hrs)

### US-11: Formulación y Solicitud de Medicamentos (5 Puntos)
- [ ] **TSK-1101:** Diseñar las entidades FormulaMedica y DetalleMedicamento. (Responsable: Dev 1 | Est.: 3 hrs)
- [ ] **TSK-1102:** Crear el endpoint POST /api/v1/medicamentos/solicitar para el despacho en farmacia. (Responsable: Dev 2 | Est.: 4 hrs)

---

## Definición de Hecho (Definition of Done - DoD)
1. El código fue subido a la rama correspondiente mediante un Pull Request.
2. Pasó revisión de código por al menos un compañero del equipo.
3. Se realizaron pruebas unitarias locales y funcionaron correctamente.
4. Cumple con todos los criterios de aceptación.