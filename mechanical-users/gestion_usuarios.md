---
title: "SOP · Gestión de Usuarios y Control de Acceso (Administración)"
description: "Guía completa para la creación, asignación de roles y permisos, gestión de seguridad y monitoreo de la actividad de todos los usuarios del sistema."
---

## Procedimiento Operativo Estándar para la Administración de Usuarios

Este SOP detalla el flujo de trabajo para administrar cuentas de usuario, incluyendo el control de roles, la configuración de seguridad y el seguimiento de actividad.

### A. Creación y Configuración Inicial de Usuarios

<Steps titleSize="h3">
  <Step title="Paso 1 · Acceso al Módulo de Usuarios" icon="user-gear" iconType="solid" stepNumber={1}>
    Inicia sesión con credenciales de administrador.
    <ul>
      <li>Navega a **"Administración"** en el menú principal.</li>
      <li>Selecciona **"Usuarios"** para ver la lista completa.</li>
    </ul>
  </Step>

  <Step title="Paso 2 · Agregar Información Básica" icon="user-plus" iconType="solid" stepNumber={2}>
    Inicia el proceso de creación de una nueva cuenta.
    <ul>
      <li>Haz clic en **"Nuevo Usuario"** (`Nuevo Usuario`).</li>
      <li>Ingresa: **Nombre Completo**, **Email** (será el username), **Teléfono** y **Departamento**.</li>
    </ul>
  </Step>

  <Step title="Paso 3 · Asignación de Rol y Permisos" icon="key" iconType="solid" stepNumber={3}>
    Define el nivel de acceso del nuevo usuario.
    <ul>
      <li>Asigna una **Contraseña Temporal** y selecciona el **Rol** (ej. `Mecánico`, `Ventas`, `Inventario`).</li>
      <li>Asigna los **Conjuntos de Permisos** (`Permission Sets`) específicos (ej. `View only`, `Create/Edit`, `Delete`).</li>
      <li>Establece una **Expiración de Cuenta** (`account expiration`) si es necesario.</li>
    </ul>
  </Step>

  <Step title="Paso 4 · Configuración Adicional" icon="cog" iconType="solid" stepNumber={4}>
    Personaliza el entorno y las preferencias.
    <ul>
      <li>Sube una **Imagen de Perfil** y configura la **Zona Horaria** (`Timezone`).</li>
      <li>Configura las **Preferencias de Notificación** y añade **Campos Personalizados** (`Custom Fields`).</li>
    </ul>
  </Step>
</Steps>

### B. Gestión de Cuentas, Equipos y Seguridad

<Steps titleSize="h3">
  <Step title="Paso 5 · Mantenimiento de Cuentas y Estado" icon="user-lock" iconType="solid" stepNumber={5}>
    Administra el ciclo de vida de las cuentas existentes.
    <ul>
      <li>Utiliza acciones rápidas para **Reiniciar Contraseña** o **Desbloquear Cuenta**.</li>
      <li>Cambia el **Estado de la Cuenta** (`Account Status`) a `Inactivo`, `Bloqueado` o `Activo`.</li>
    </ul>
  </Step>

  <Step title="Paso 6 · Creación y Gestión de Equipos" icon="users" iconType="solid" stepNumber={6}>
    Organiza a los usuarios en grupos de trabajo.
    <ul>
      <li>Ve a **"Equipos"** (`Equipos`) y haz clic en **"Nuevo Equipo"**.</li>
      <li>Añade **Miembros del Equipo** (`team members`) y asigna **Permisos de Equipo** para funcionalidades compartidas.</li>
    </ul>
  </Step>

  <Step title="Paso 7 · Aplicación de Políticas de Seguridad" icon="shield-alt" iconType="solid" stepNumber={7}>
    Fortalece la seguridad del sistema y las cuentas.
    <ul>
      <li>Asegúrate de que las **Políticas de Contraseña** cumplan con la **longitud mínima (12 caracteres)** y **expiración (90 días)**.</li>
      <li>**Habilita la Autenticación de Dos Factores (2FA)** y documenta las opciones de recuperación.</li>
    </ul>
  </Step>

  <Step title="Paso 8 · Monitoreo y Auditoría de Actividad" icon="search-dollar" iconType="solid" stepNumber={8}>
    Sigue los cambios y accesos de los usuarios.
    <ul>
      <li>Revisa los **Registros de Actividad** (`Activity Logs`) para intentos de inicio de sesión y cambios al sistema.</li>
      <li>Genera **Reportes de Auditoría** (`Audit Reports`) sobre el historial de acceso y cambios de permisos.</li>
    </ul>
  </Step>
</Steps>

---

### Cautionary Notes

- **Problemas de Permisos:** Si un usuario reporta que le faltan funcionalidades, verifica su **Asignación de Rol** y los **Conjuntos de Permisos** aplicados en el Paso 3.
- **Offboarding:** Al dar de baja a un usuario, **Deshabilita la cuenta inmediatamente**, transfiere sus responsabilidades y archiva sus datos para mantener la seguridad.

### Tips for Efficiency

- **Onboarding:** Usa una **plantilla de email de bienvenida** y **asigna un mentor** (`mentor/buddy`) para acelerar la integración de nuevos usuarios.
- **Roles Personalizados:** Utiliza la función de **Roles Personalizados** (`Custom Roles`) para clonar roles existentes y ajustarlos, en lugar de comenzar desde cero.