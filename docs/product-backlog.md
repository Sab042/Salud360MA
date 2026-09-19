# Product Backlog - SALUD360

## Información del Proyecto
- **Proyecto:** SALUD360
- **Metodología:** SCRUM
- **Descripción:** Sistema para la solicitud de citas médicas, consulta de historia clínica, registro de visitas y gestión de medicamentos.

---

## Estratificación del Backlog: Épicas y Features

### 1. Épica: Gestión de Usuarios, Roles y Seguridad
**Descripción:** Administración del acceso, autenticación de usuarios y asignación de roles dentro del sistema.

* **Feature 1.1: Autenticación y Control de Sesión**
  * Inicio de sesión (Login) y cierre de sesión (Logout).
  * Recuperación y cambio de contraseña.
* **Feature 1.2: Gestión de Cuentas y Perfiles**
  * Registro de cuentas de usuarios y asignación de roles (Paciente, Médico, IPS, Administrador).
  * Gestión y actualización de datos de perfil.

---

### 2. Épica: Administración de Entidades y Recursos Médicos
**Descripción:** Mantenimiento de la información base necesaria de los recursos de la institución de salud.

* **Feature 2.1: Gestión del Personal Médico**
  * CRUD (Crear, Leer, Actualizar, Eliminar) de Médicos.
  * Asignación de especialidades y configuración de horarios de atención.
* **Feature 2.2: Gestión de IPS**
  * CRUD de sedes e instituciones prestadoras de salud (IPS).
* **Feature 2.3: Gestión de Consultorios**
  * CRUD de consultorios e instalaciones.

---

### 3. Épica: Gestión de Agendamiento y Citas Médicas
**Descripción:** Flujo completo para la búsqueda, reserva y control de citas médicas por parte del paciente.

* **Feature 3.1: Reserva de Citas Médicas**
  * Búsqueda de disponibilidad por especialista, IPS o fecha.
  * Solicitud y confirmación de cita médica.
* **Feature 3.2: Control y Seguimiento de Citas**
  * Reprogramación y cancelación de citas médicas.

---

### 4. Épica: Gestión de Historias Clínicas y Expedientes Médicos
**Descripción:** Registro y consulta de la información médica relevante del paciente.

* **Feature 4.1: Solicitud y Consulta de Historia Clínica**
  * Generación y visualización de la historia clínica digital del paciente.
* **Feature 4.2: Registro de Atenciones Médicas**
  * Registro de diagnósticos, observaciones y evoluciones clínicas por parte del profesional.

---

### 5. Épica: Gestión de Visitas y Seguimiento del Paciente
**Descripción:** Control de asistencia y trazabilidad del paciente en las instalaciones.

* **Feature 5.1: Historial y Registro de Visitas**
  * Registro de asistencia/check-in al llegar al centro médico.
  * Visualización del historial de visitas del paciente.

---

### 6. Épica: Gestión de Prescripciones y Medicamentos
**Descripción:** Administración de recetas y solicitudes de medicamentos formulados.

* **Feature 6.1: Solicitud y Emisión de Medicamentos**
  * Solicitud de despacho de medicamentos.
  * Consulta e historial de fórmulas médicas prescritas.