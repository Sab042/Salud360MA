# Sprint Backlog - Sprint 3

## Información General del Sprint
- **Sprint:** 3
- **Fecha de inicio:** 17 de Octubre, 2026
- **Fecha de fin:** 31 de Octubre, 2026
- **Objetivo del Sprint (Sprint Goal):** Desarrollar el motor de agendamiento de citas médicas en tiempo real y el flujo de gestión de llegadas (check-in) de pacientes en sede.

---

## Historias de Usuario Seleccionadas (Sprint Scope)

| ID | Historia de Usuario | Puntos de Historia | Prioridad | Estado |
| :--- | :--- | :---: | :---: | :---: |
| **US-06** | Búsqueda y Reserva de Citas | 8 | Alta | Pendiente |
| **US-07** | Reprogramación y Cancelación de Citas | 5 | Media | Pendiente |
| **US-10** | Check-in y Registro de Visita | 3 | Media | Pendiente |

*Total de Puntos de Historia del Sprint:* 16 Puntos

---

## Desglose de Tareas Técnicas (Task Breakout)

### US-06: Búsqueda y Reserva de Citas (8 Puntos)
- [ ] **TSK-601:** Diseñar el modelo de datos CitaMedica con relaciones a Paciente, Medico, IPS y Estado. (Responsable: Dev 1 | Est.: 4 hrs)
- [ ] **TSK-602:** Implementar el algoritmo de búsqueda de disponibilidad de horarios cruzando agenda médica e IPS. (Responsable: Dev 1 | Est.: 6 hrs)
- [ ] **TSK-603:** Crear el endpoint POST /api/v1/citas/reservar con control de concurrencia para evitar sobre-agendamiento. (Responsable: Dev 2 | Est.: 5 hrs)
- [ ] **TSK-604:** Construir el servicio de generación de comprobantes y confirmación de cita. (Responsable: Dev 2 | Est.: 3 hrs)

### US-07: Reprogramación y Cancelación de Citas (5 Puntos)
- [ ] **TSK-701:** Crear el servicio para validar restricción de cancelación con mínimo 24 horas de anticipación. (Responsable: Dev 1 | Est.: 3 hrs)
- [ ] **TSK-702:** Implementar la lógica para liberar automáticamente el bloque horario cancelado. (Responsable: Dev 2 | Est.: 3 hrs)

### US-10: Check-in y Registro de Visita (3 Puntos)
- [ ] **TSK-1001:** Crear el endpoint PUT /api/v1/citas/{id}/checkin para recepcionistas. (Responsable: Dev 1 | Est.: 2 hrs)
- [ ] **TSK-1002:** Actualizar estado de la cita a "En Sala de Espera" y notificar al panel del médico. (Responsable: Dev 2 | Est.: 3 hrs)

---

## Definición de Hecho (Definition of Done - DoD)
Para considerar una Historia de Usuario como completada en este Sprint debe cumplir con:
1. El código fue subido a la rama correspondiente mediante un Pull Request.
2. Pasó revisión de código por al menos un compañero del equipo.
3. Se realizaron pruebas unitarias locales y funcionaron correctamente.
4. Cumple con todos los criterios de aceptación especificados en la Historia de Usuario.