---
title: "SOP · Gestión Integral de Órdenes de Servicio (Órdenes de Taller)"
description: "Guía completa para la creación, gestión, facturación y seguimiento de órdenes de servicio, optimizando el flujo de trabajo del taller."
---

## Procedimiento Operativo Estándar para la Gestión de Órdenes

Este SOP describe el proceso integral para la gestión de órdenes de servicio, desde la creación de la orden hasta la facturación y el seguimiento post-servicio.

### A. Creación de una Nueva Orden de Servicio

<Steps titleSize="h3">
  <Step title="Paso 1 · Iniciar Nueva Orden" icon="file-circle-plus" iconType="solid" stepNumber={1}>
    Accede al módulo de órdenes y selecciona el cliente.
    <ul>
      <li>Navega a **"Órdenes de Servicio"** y haz clic en **"Nueva Orden"** (`Nueva Orden`).</li>
      <li>Selecciona el cliente de la base de datos o crea un nuevo perfil.</li>
    </ul>
  </Step>

  <Step title="Paso 2 · Registrar Información del Vehículo" icon="car" iconType="solid" stepNumber={2}>
    Captura los datos esenciales del vehículo.
    <ul>
      <li>Selecciona un vehículo existente o añade uno nuevo.</li>
      <li>Ingresa: Marca, modelo, año, Placa, VIN y **Kilometraje Actual**.</li>
    </ul>
  </Step>

  <Step title="Paso 3 · Añadir Servicios y Partes" icon="list-check" iconType="solid" stepNumber={3}>
    Detalla el trabajo y los materiales necesarios.
    <ul>
      <li>Busca y añade servicios del **catálogo**.</li>
      <li>Añade **partes** del inventario o crea una solicitud de pedido.</li>
      <li>Establece cantidades, precios y aplica descuentos si es necesario.</li>
    </ul>
  </Step>
</Steps>

### B. Gestión y Flujo de Trabajo

<Steps titleSize="h3">
  <Step title="Paso 4 · Asignar Técnico y Prioridad" icon="user-gear" iconType="solid" stepNumber={4}>
    Asigna la orden y define su urgencia.
    <ul>
      <li>Abre la orden, ve a **"Asignar Técnico"** (`Asignar Técnico`).</li>
      <li>Selecciona el mecánico y **establece el nivel de prioridad** de la tarea.</li>
    </ul>
  </Step>

  <Step title="Paso 5 · Monitoreo y Actualización de Estado" icon="rotate" iconType="solid" stepNumber={5}>
    Sigue el progreso y actualiza el estado en tiempo real.
    <ul>
      <li>Utiliza **"Actualizar Estado"** para cambiar la orden a: `En Progreso`, `Esperando Repuestos`, `Listo para Revisión`, etc.</li>
      <li>**Añade Notas** (`Agregar Nota`) sobre hallazgos y adjunta fotos/archivos (`Attach Files`).</li>
    </ul>
  </Step>

  <Step title="Paso 6 · Finalización y Facturación" icon="receipt" iconType="solid" stepNumber={6}>
    Cierra la orden y procesa el pago.
    <ul>
      <li>Asegúrate de que todos los trabajos estén listos (`Listo para Entrega`).</li>
      <li>Haz clic en **"Generar Factura"** y selecciona el método de pago: `Efectivo`, `Tarjeta`, `Transferencia`, etc.</li>
    </ul>
  </Step>
</Steps>

---

### Cautionary Notes

- **Aprobación de Cliente:** Para trabajo adicional, **documenta la aprobación del cliente** (digitalmente o anotando la aprobación verbal) antes de proceder con el trabajo.
- **Repuestos Faltantes:** Si faltan partes (`Missing Parts`), **actualiza el estado a "Esperando Repuestos"**, notifica al cliente y registra la fecha de entrega esperada.

### Tips for Efficiency

- **Control de Calidad:** Antes de cerrar la orden y facturar, realiza un control de calidad y **toma fotos del "después"** si es necesario.
- **Informes:** Revisa regularmente los **Reportes** (`Reports`) de `Productividad del Mecánico` y `Servicios Pendientes` para detectar cuellos de botella.
- **Estimaciones:** Utiliza la función de **Estimaciones** (`Estimates`) para enviar cotizaciones; si se aprueban, **conviértelas directamente** a órdenes de servicio.