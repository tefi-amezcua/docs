---
title: "SOP · Configuración y Ajustes del Taller (Workshop Settings)"
description: "Guía completa para configurar la información básica, reglas de citas, tarifas de servicio, notificaciones, integraciones y seguridad del sistema."
---

## Procedimiento Operativo Estándar para Configurar el Taller

Este SOP describe cómo un administrador debe configurar y mantener los ajustes operativos, de servicio y de seguridad del taller a través del menú de **Configuración del Taller**.

### A. Información Básica y Configuración de Servicio

<Steps titleSize="h3">
  <Step title="Paso 1 · Acceso a la Configuración" icon="cog" iconType="solid" stepNumber={1}>
    Inicia sesión con credenciales de administrador y navega al menú.
    <ul>
      <li>Haz clic en tu **Foto de Perfil** o en el menú de usuario.</li>
      <li>Selecciona **"Configuración del Taller"** (`Configuración del Taller`).</li>
    </ul>
  </Step>

  <Step title="Paso 2 · Detalle del Taller y Ubicación" icon="building" iconType="solid" stepNumber={2}>
    Define la identidad y los parámetros básicos del negocio.
    <ul>
      <li>Actualiza el **Nombre y Logotipo** del taller y la **Información de Contacto**.</li>
      <li>Establece los **Horarios Comerciales** (`Business hours`), la **Zona Horaria** y el **Formato de Moneda**.</li>
      <li>Ingresa la **Dirección Física** y las **Áreas de Servicio** (`Service areas`).</li>
    </ul>
  </Step>

  <Step title="Paso 3 · Definición de Tipos de Servicio y Tarifas" icon="tags" iconType="solid" stepNumber={3}>
    Configura la estructura de los servicios ofrecidos.
    <ul>
      <li>Define las **Categorías de Servicio** (`Service Types`) y las **Duraciones Predeterminadas**.</li>
      <li>Establece los **Tiempos de Buffer** (`Buffer times`) y las **Tarifas de Mano de Obra** (`Labor rates`).</li>
      <li>Configura los **Impuestos** aplicables y los **Cargos Mínimos** (`Minimum charges`).</li>
    </ul>
  </Step>
</Steps>

### B. Reglas de Agendamiento, Personal y Comunicación

<Steps titleSize="h3">
  <Step title="Paso 4 · Configuración de Reglas de Citas" icon="calendar-check" iconType="solid" stepNumber={4}>
    Establece los parámetros para la reserva de citas en la agenda.
    <ul>
      <li>Define el **Aviso Mínimo** (`Minimum notice`) y el **Máximo de Días de Anticipación** para reservas.</li>
      <li>Configura los **Incrementos de Franjas Horarias** (`Time slot increments`).</li>
    </ul>
  </Step>

  <Step title="Paso 5 · Configuración de Notificaciones" icon="bell" iconType="solid" stepNumber={5}>
    Personaliza las comunicaciones automáticas con el cliente.
    <ul>
      <li>Edita las **Plantillas de Email** (`Email templates`) y los **Mensajes SMS** (`SMS notifications`).</li>
      <li>Establece la frecuencia y el contenido de los **Recordatorios** y los **Mensajes de Seguimiento** (`Follow-up messages`).</li>
    </ul>
  </Step>

  <Step title="Paso 6 · Administración del Equipo y Métricas" icon="users" iconType="solid" stepNumber={6}>
    Gestiona a tu personal y define objetivos de rendimiento.
    <ul>
      <li>Define **Horarios de Trabajo** y gestiona las **Ausencias** (`Time off management`).</li>
      <li>Asigna **Habilidades** (`Skill assignments`) y establece **Métricas de Rendimiento** (`Performance Metrics`) como **Objetivos de Servicio** y **Estándares de Calidad**.</li>
    </ul>
  </Step>
</Steps>

### C. Integraciones, Seguridad y Mantenimiento

<Steps titleSize="h3">
  <Step title="Paso 7 · Integración de Calendario y Pagos" icon="cloud-arrow-up" iconType="solid" stepNumber={7}>
    Conecta el sistema con herramientas externas clave.
    <ul>
      <li>Sincroniza el calendario con **Google Calendar** u **Outlook Calendar**.</li>
      <li>Configura **Pasarelas de Pago** (`Payment Processors`) y establece **Requisitos de Depósito** (`deposit requirements`).</li>
    </ul>
  </Step>

  <Step title="Paso 8 · Ajustes Avanzados y Automatización" icon="wand-magic-sparkles" iconType="solid" stepNumber={8}>
    Personaliza el sistema con campos y flujos de trabajo.
    <ul>
      <li>Añade **Campos Personalizados** (`Custom Fields`) a órdenes de servicio o perfiles de cliente/vehículo.</li>
      <li>Configura **Automatizaciones de Flujo de Trabajo** (`Workflow Automation`) como disparadores por cambio de estado (`Status change triggers`).</li>
    </ul>
  </Step>

  <Step title="Paso 9 · Seguridad y Mantenimiento de Datos" icon="lock" iconType="solid" stepNumber={9}>
    Implementa políticas de seguridad y gestión de datos.
    <ul>
      <li>Programa **Copias de Seguridad** (`Schedule backups`) y define **Políticas de Retención de Datos** (`Data retention policies`).</li>
      <li>Establece **Políticas de Contraseña** (`Password policies`), **Tiempo de Espera de Sesión** (`Session timeout`) y **Restricciones de IP**.</li>
    </ul>
  </Step>
</Steps>

---

### Cautionary Notes

- **Fallas de Sincronización:** Si hay problemas de sincronización de calendario (`Calendar sync issues`), verifica la **Conexión de la API** (`API connections`) y las credenciales de la cuenta externa.
- **Notificaciones:** Si las notificaciones fallan, **revisa y prueba** las configuraciones de email/SMS en el sistema.

### Tips for Efficiency

- **Mantenimiento Regular:** **Revisa la configuración trimestralmente** y **actualiza los horarios comerciales** antes de días festivos para evitar errores en la agenda.
- **Capacitación:** Documenta los cambios de configuración y **capacita al equipo** sobre las actualizaciones para asegurar su correcto uso.