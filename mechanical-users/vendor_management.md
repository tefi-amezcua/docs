---
title: "SOP · Gestión Integral de Proveedores (Vendor Management)"
description: "Guía completa para la administración, seguimiento de rendimiento, procesamiento de órdenes de compra y gestión de pagos a proveedores."
---

## Procedimiento Operativo Estándar para la Gestión de Proveedores

Este SOP detalla el flujo de trabajo para administrar proveedores, desde su registro inicial hasta la emisión de órdenes de compra, recepción de inventario y procesamiento de pagos.

### A. Registro y Administración de Proveedores

<Steps titleSize="h3">
  <Step title="Paso 1 · Acceso a Gestión de Proveedores" icon="handshake" iconType="solid" stepNumber={1}>
    Inicia sesión con credenciales de administrador.
    <ul>
      <li>Navega a **"Proveedores"** en el menú principal.</li>
      <li>Selecciona **"Gestión de Proveedores"**.</li>
    </ul>
  </Step>

  <Step title="Paso 2 · Agregar Nuevo Proveedor" icon="user-plus" iconType="solid" stepNumber={2}>
    Crea un nuevo perfil de proveedor en el sistema.
    <ul>
      <li>Haz clic en **"Nuevo Proveedor"** (`Nuevo Proveedor`).</li>
      <li>Ingresa: **Nombre de la Compañía**, **Contacto**, **Email/Teléfono** e **ID Fiscal**.</li>
      <li>Establece los **Términos de Pago** (`Payment terms`) y el **Tiempo de Entrega** (`Lead time`).</li>
    </ul>
  </Step>

  <Step title="Paso 3 · Monitoreo de Información y Rendimiento" icon="chart-simple" iconType="solid" stepNumber={3}>
    Mantén la información de contacto y de rendimiento actualizada.
    <ul>
      <li>Actualiza direcciones y **añade múltiples contactos** si es necesario.</li>
      <li>Revisa las **Calificaciones de Calidad** (`Quality ratings`) y la **Tasa de Entrega a Tiempo** (`On-time delivery rate`).</li>
    </ul>
  </Step>
</Steps>

### B. Órdenes de Compra y Recepción

<Steps titleSize="h3">
  <Step title="Paso 4 · Crear una Orden de Compra (PO)" icon="file-invoice-dollar" iconType="solid" stepNumber={4}>
    Genera una nueva solicitud de compra al proveedor.
    <ul>
      <li>Ve a **"Órdenes de Compra"** y haz clic en **"Nueva Orden"**.</li>
      <li>Selecciona el proveedor, añade los artículos, cantidades y la **Fecha de Entrega**.</li>
      <li>Envía para aprobación, observando el cambio de estado (Draft > Sent > **Confirmed**).</li>
    </ul>
  </Step>

  <Step title="Paso 5 · Recepción y Control de Calidad" icon="truck-loading" iconType="solid" stepNumber={5}>
    Registra la mercancía recibida y verifica su calidad.
    <ul>
      <li>Navega a **"Recepción"** (`Recepción`), selecciona la PO correspondiente.</li>
      <li>**Verifica** los artículos recibidos, **actualiza el inventario** y genera el reporte de recepción.</li>
      <li>**Documenta** cualquier discrepancia o problema de calidad.</li>
    </ul>
  </Step>

  <Step title="Paso 6 · Procesamiento de Pagos" icon="credit-card" iconType="solid" stepNumber={6}>
    Administra las facturas pendientes y los términos de pago.
    <ul>
      <li>Revisa las **Facturas Pendientes** (`outstanding invoices`).</li>
      <li>Procesa el pago y asegúrate de aplicar términos como **Net 30/60** o **Descuentos por Pago Anticipado** (`Early payment discounts`).</li>
    </ul>
  </Step>
</Steps>

---

### Cautionary Notes

- **Problemas de Calidad:** En caso de **Problemas de Calidad** (`Quality issues`), documenta inmediatamente las fallas y utiliza el sistema para **reportar discrepancias**.
- **Tiempos de Entrega:** Si hay **Entregas Tardías** (`Late deliveries`), revisa los **KPIs** y notifica al proveedor formalmente, documentando la interacción.

### Tips for Efficiency

- **Relaciones Clave:** **Programa revisiones regulares** (`Schedule regular reviews`) con los proveedores estratégicos para mantener una comunicación constante y proveer *feedback*.
- **Informes Proactivos:** Utiliza los **Reportes de Proveedores** (`Vendor Reports`) para el **Análisis de Gasto** (`Spending analysis`) y los **Reportes de Inventario** (`Inventory Reports`) para anticipar puntos de reorden.