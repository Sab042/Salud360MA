# Historias de Usuario - SALUD360

---

## Módulo: Gestión de Usuarios y Seguridad

### US-01: Registro de usuario
**Como:** Paciente  
**Quiero:** Crear una cuenta en la plataforma  
**Para:** Acceder a los servicios de agendamiento y consulta médica.

#### Criterios de Aceptación:
- El usuario debe ingresar nombre completo, documento, correo y contraseña.
- El sistema debe validar que el correo no esté registrado previamente.
- El sistema debe validar la fortaleza de la contraseña.
- El usuario debe recibir un mensaje de confirmación tras el registro.

* **Prioridad:** Alta  
* **Estimación:** 5 puntos  

---

### US-02: Inicio de sesión
**Como:** Usuario registrado (Paciente/Médico)  
**Quiero:** Iniciar sesión con mi correo y contraseña  
**Para:** Acceder a mi panel personal de forma segura.

#### Criterios de Aceptación:
- El sistema debe verificar las credenciales ingresadas.
- Si los datos son incorrectos, debe mostrar un mensaje de error claro.
- Al autenticarse correctamente, redirecciona al tablero principal según el rol.

* **Prioridad:** Alta  
* **Estimación:** 3 puntos  

---

## Módulo: Agendamiento de Citas Médicas

### US-03: Solicitud de Cita Médica
**Como:** Paciente  
**Quiero:** Buscar disponibilidad de agendas por médico o especialidad  
**Para:** Reservar una cita médica en el horario de mi preferencia.

#### Criterios de Aceptación:
- El paciente puede filtrar por especialidad, IPS y fecha.
- El sistema muestra los turnos disponibles en tiempo real.
- Al confirmar la reserva, se envía una notificación de confirmación al paciente.

* **Prioridad:** Alta  
* **Estimación:** 8 puntos  

---

## Módulo: Historia Clínica

### US-04: Consulta de Historia Clínica
**Como:** Paciente  
**Quiero:** Visualizar mi historial médico y diagnósticos previos  
**Para:** Hacer seguimiento a mi estado de salud e indicaciones médicas.

#### Criterios de Aceptación:
- Solo el paciente autenticado o el médico asignado pueden ver el registro.
- Los registros deben ordenarse de forma cronológica descendente.
- Debe permitir la opción de exportar/descargar el informe en formato PDF.

* **Prioridad:** Media  
* **Estimación:** 5 puntos