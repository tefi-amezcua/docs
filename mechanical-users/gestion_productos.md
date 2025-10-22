---
title: "SOP · Gestión de Productos e Inventario (Integración con Shopify)"
description: "Guía completa para la administración manual y masiva de productos, gestión de inventario, categorización y configuración de la sincronización con Shopify."
---

## Procedimiento Operativo Estándar para la Gestión de Productos

Este SOP detalla el flujo de trabajo para la administración de productos, incluyendo la importación desde Shopify y el control avanzado del inventario.

### A. Creación y Configuración Manual de Productos

<Steps titleSize="h3">
  <Step title="Paso 1 · Acceso al Módulo de Productos" icon="box-open" iconType="solid" stepNumber={1}>
    Accede al sistema con credenciales de administrador.
    <ul>
      <li>Navega a **"Productos"** en el menú principal.</li>
      <li>Selecciona **"Gestión de Productos"**.</li>
    </ul>
  </Step>

  <Step title="Paso 2 · Agregar Información Básica y Precios" icon="tag" iconType="solid" stepNumber={2}>
    Crea un nuevo producto y define sus atributos.
    <ul>
      <li>Haz clic en **"Nuevo Producto"** (`Nuevo Producto`).</li>
      <li>Rellena: **Nombre**, **Descripción**, **SKU**, **Categoría** y **Marca**.</li>
      <li>Establece el **Precio base** y el **Costo** del producto.</li>
    </ul>
  </Step>

  <Step title="Paso 3 · Gestionar Variaciones y Stock" icon="layer-group" iconType="solid" stepNumber={3}>
    Configura las opciones del producto y los niveles de inventario.
    <ul>
      <li>Crea opciones de variación (ej. Tallas, Colores) y sus precios individuales.</li>
      <li>Define el **Nivel de Stock Mínimo** (`minimum stock level`) y la información del proveedor.</li>
    </ul>
  </Step>
</Steps>

### B. Integración y Sincronización con Shopify

<Steps titleSize="h3">
  <Step title="Paso 4 · Iniciar Proceso de Importación" icon="shop" iconType="solid" stepNumber={4}>
    Sincroniza productos y colecciones de tu tienda Shopify.
    <ul>
      <li>Ve a **"Importar"** > **"Desde Shopify"**.</li>
      <li>**Mapea los campos** de Shopify con los campos de tu sistema.</li>
    </ul>
  </Step>

  <Step title="Paso 5 · Configurar Preferencias de Sincronización" icon="arrows-rotate" iconType="solid" stepNumber={5}>
    Define cómo se gestionarán los datos importados.
    <ul>
      <li>Establece preferencias: **Actualizar existentes**, **Crear nuevos**, y cómo manejar artículos sin stock.</li>
      <li>Selecciona el tipo de sincronización: **Manual**, **Programada** o **Tiempo Real** (`Real-time Sync`).</li>
    </ul>
  </Step>

  <Step title="Paso 6 · Importar y Mapear Categorías" icon="folder-tree" iconType="solid" stepNumber={6}>
    Asegura que las categorías se reflejen correctamente.
    <ul>
      <li>Ve a **"Importar"** > **"Categorías desde Shopify"**.</li>
      <li>**Mapea las colecciones** de Shopify a las categorías de tu sistema.</li>
    </ul>
  </Step>
</Steps>

### C. Gestión de Inventario y Precios

<Steps titleSize="h3">
  <Step title="Paso 7 · Control de Stock y Transferencias" icon="warehouse" iconType="solid" stepNumber={7}>
    Monitorea y ajusta los niveles de inventario.
    <ul>
      <li>Revisa **niveles de stock** y **Puntos de Reorden** (`reorder points`).</li>
      <li>Utiliza la función **Transferencia de Stock** (`Stock Transfers`) para mover inventario entre ubicaciones.</li>
    </ul>
  </Step>

  <Step title="Paso 8 · Aplicar Precios y Promociones" icon="dollar-sign" iconType="solid" stepNumber={8}>
    Define estrategias de precio avanzadas.
    <ul>
      <li>Crea **Listas de Precios** (`Price Lists`) para diferentes niveles de clientes.</li>
      <li>Configura **Descuentos y Promociones** automáticas o genera códigos.</li>
    </ul>
  </Step>

  <Step title="Paso 9 · Actualizaciones Masivas y Mantenimiento" icon="upload" iconType="solid" stepNumber={9}>
    Realiza cambios rápidos y globales en la información.
    <ul>
      <li>Utiliza la herramienta de **Actualizaciones Masivas** (`Bulk Updates`) para cambiar precios o categorías.</li>
      <li>Optimiza las **Imágenes de Producto** y asegúrate de la correcta **categorización**.</li>
    </ul>
  </Step>
</Steps>

---

### Cautionary Notes

- **Fallas de Sincronización:** Si la sincronización falla (`Sync failures`), verifica la **conexión de la API** y los permisos configurados entre Shopify y el sistema.
- **Precios Incorrectos:** Si hay problemas de precios (`Pricing issues`), revisa las **reglas de listas de precios** y los descuentos aplicados.

### Tips for Efficiency

- **Mantenimiento de Datos:** Realiza **conteos de inventario regulares** (`Regular inventory counts`) y archiva inmediatamente los artículos descontinuados para mantener la base de datos limpia.
- **Reportes:** Utiliza los **Reportes de Inventario** (`Inventory Reports`) y **Alertas de Bajo Stock** (`Low stock alerts`) para una toma de decisiones proactiva.