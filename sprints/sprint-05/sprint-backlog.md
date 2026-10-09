# Sprint Backlog - Sprint 5

## Información General del Sprint
- **Sprint:** 5
- **Fecha de inicio:** 16 de Noviembre, 2026
- **Fecha de fin:** 30 de Noviembre, 2026
- **Objetivo del Sprint (Sprint Goal):** Implementar la formulación, prescripción y gestión de solicitudes de despacho de medicamentos hacia las farmacias asignadas.

---

## Historias de Usuario Seleccionadas (Sprint Scope)

| ID | Historia de Usuario | Puntos de Historia | Prioridad | Estado |
| :--- | :--- | :---: | :---: | :---: |
| **US-11** | Formulación y Solicitud de Medicamentos | 5 | Media | Pendiente |

**Total de Puntos de Historia del Sprint:** 5 Puntos

---

## Desglose de Tareas Técnicas (Task Breakout)

### US-11: Formulación y Solicitud de Medicamentos (5 Puntos)
- [ ] **TSK-1101:** Diseñar las entidades `FormulaMedica` y `DetalleMedicamento` vinculadas a la atención médica.
- [ ] **TSK-1102:** Crear el endpoint POST `/api/v1/medicamentos/prescribir` para que el médico registre la orden.
- [ ] **TSK-1103:** Crear el endpoint GET `/api/v1/medicamentos/paciente/{id}` para consultar recetas activas e historial.
- [ ] **TSK-1104:** Implementar la lógica para enviar solicitudes de despacho de medicamentos a la farmacia de la IPS.

---

## Definición de Hecho (Definition of Done - DoD)
Para considerar una Historia de Usuario como completada en este Sprint debe cumplir con:
1. El código fue subido a la rama correspondiente mediante un Pull Request.
2. Pasó revisión de código por al menos un compañero del equipo.
3. Se realizaron pruebas unitarias locales y funcionaron correctamente.
4. Cumple con todos los criterios de aceptación especificados en la Historia de Usuario.

---