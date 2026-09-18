# T4_Asertiva
Tarea 4 - Comunicación Asertiva
# Propuesta de Estrategia de Comunicación y Gestión para Equipos de Desarrollo de Software Distribuidos

## 1. Resumen Ejecutivo

El presente documento establece un marco operativo de comunicación asertiva y coordinación técnica diseñado para optimizar los flujos de trabajo en equipos de desarrollo de software que operan bajo modalidades virtuales. La propuesta busca mitigar la dispersión de la información, reducir la ambigüedad en los requerimientos y promover la responsabilidad individual y colectiva.

---

## 2. Componentes de la Estrategia

### 2.1. Reglas de Netiqueta
- **Tono Profesional y Orientado a Soluciones:** Las interacciones, revisiones y correcciones deben enfocar el análisis objetivamente en el artefacto o código, evitando sesgos personales y empleando una redacción respetuosa y constructiva.
- **Respeto a la Comunicación Asíncrona:** Se prioriza la documentación estructurada y se respetan las franjas de disponibilidad operativa definidas por la organización.

### 2.2. Gestión de Hilos de Conversación y Niveles de Prioridad
- **Uso Estricto de Hilos (Threads):** Toda aclaración, debate o seguimiento sobre un requerimiento específico debe realizarse exclusivamente dentro del hilo correspondiente para conservar el contexto y evitar la saturación de los canales generales.
- **Clasificación por Prioridades:** Todo mensaje o notificación debe categorizarse utilizando los siguientes prefijos normativos:
  - `[PRIORIDAD: CRÍTICA]`: Asuntos que bloquean el entorno de producción o impiden el avance operativo. Requiere atención inmediata.
  - `[PRIORIDAD: MEDIA]`: Solicitudes operativas estándar que deben ser atendidas dentro de la jornada laboral.
  - `[PRIORIDAD: BAJA]`: Notificaciones informativas, minutas o actualizaciones generales que no requieren respuesta inmediata.

### 2.3. Herramientas Colaborativas de Ingeniería
- **GitHub Issues:** Constituye la única fuente de verdad para el registro, asignación y seguimiento de requerimientos, errores e hitos del proyecto.
- **Pull Requests (PR):** Todo cambio en la base de código debe ser vinculado a un Issue específico mediante un Pull Request. Se establece la obligatoriedad de al menos una revisión por pares (Peer Review) técnica antes de realizar la integración a la rama principal.

### 2.4. Ownership y Custodia de Documentación
- Cada documento técnico, diagrama de arquitectura o guía de despliegue contará con un Propietario (Owner) designado.
- **Responsabilidades del Owner:** Garantizar la vigencia, precisión técnica y actualización periódica del documento, así como resolver observaciones o propuestas de modificación por parte de otros miembros del equipo.

### 2.5. Gobernanza y Roles en Reuniones Remotas
Para garantizar la eficiencia en las sesiones sincrónicas, se definen los siguientes roles rotativos:
- **Moderador:** Encargado de definir la agenda previa, dirigir el flujo de la sesión, conceder la palabra y sintetizar los acuerdos adoptados.
- **Timekeeper:** Responsable del control riguroso del tiempo asignado a cada punto del orden del día, asegurando el cumplimiento de la duración estipulada para la reunión.

### 2.6. Plan de Contingencia (Fallback Plan)
- **Fallo en Conectividad Individual:** Notificación inmediata mediante el canal secundario de mensajería corporativa especificado para contingencias.
- **Fallo en Plataforma Principal de Videoconferencia:** En caso de interrupción del servicio primario, el equipo realizará la migración automática a la sala de sesiones de respaldo previamente configurada en la plataforma secundaria.

---

## 3. Enlace a la Presentación (Pitch)
