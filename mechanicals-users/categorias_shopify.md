---
title: "SOP · Gestión de Categorías de Productos e Importación desde Shopify"
description: "Guía paso a paso para la creación, organización jerárquica, optimización SEO e importación masiva de categorías desde colecciones de Shopify."
---

## Procedimiento Operativo Estándar para la Gestión de Categorías

Este SOP describe cómo utilizar el módulo de categorías para estructurar el catálogo, organizar la jerarquía y sincronizar colecciones desde Shopify.

### A. Creación y Organización Manual de Categorías

<Steps titleSize="h3">
  <Step title="Paso 1 · Acceso a Gestión de Categorías" icon="folder-tree" iconType="solid" stepNumber={1}>
    Inicia sesión con credenciales de administrador.
    <ul>
      <li>Ve a **"Catálogo"** en el menú principal.</li>
      <li>Selecciona **"Categorías"** y revisa la jerarquía existente.</li>
    </ul>
  </Step>

  <Step title="Paso 2 · Configuración Básica y SEO" icon="plus" iconType="solid" stepNumber={2}>
    Crea una nueva categoría y añade información esencial para la web.
    <ul>
      <li>Haz clic en **"Nueva Categoría"** (`Nueva Categoría`).</li>
      <li>Rellena el **Nombre** (ej. "Frenos"), la **Categoría Padre** y la **Descripción**.</li>
      <li>Ingresa el **Título y Descripción SEO** (`SEO Title and Description`).</li>
    </ul>
  </Step>

  <Step title="Paso 3 · Organización de la Jerarquía" icon="sort-alpha-down" iconType="solid" stepNumber={3}>
    Estructura el catálogo para facilitar la navegación del cliente.
    <ul>
      <li>Utiliza la función de **Arrastrar y Soltar** (`Drag and drop`) para reordenar las categorías.</li>
      <li>Crea **categorías anidadas** o subcategorías, limitando la profundidad a un máximo de 3 niveles.</li>
    </ul>
  </Step>
</Steps>

### B. Importación desde Shopify y Asignación de Productos

<Steps titleSize="h3">
  <Step title="Paso 4 · Iniciar Importación de Colecciones" icon="cloud-arrow-down" iconType="solid" stepNumber={4}>
    Sincroniza la estructura de categorías desde tu tienda Shopify.
    <ul>
      <li>Ve a **"Importar"** > **"Desde Shopify"** > **"Categorías"**.</li>
      <li>Selecciona las colecciones que deseas importar al sistema.</li>
    </ul>
  </Step>

  <Step title="Paso 5 · Mapeo de Campos e Importación" icon="link" iconType="solid" stepNumber={5}>
    Configura la transferencia de datos y ejecuta la importación.
    <ul>
      <li>**Mapea campos** (ej. `Collection Name` → `Category Name`).</li>
      <li>Define opciones de importación: **Actualizar existentes** o **Crear nuevas**.</li>
      <li>Haz clic en **"Iniciar Importación"** (`Iniciar Importación`) y revisa el resultado.</li>
    </ul>
  </Step>

  <Step title="Paso 6 · Asignación de Productos y Actualizaciones Masivas" icon="tags" iconType="solid" stepNumber={6}>
    Vincula los productos a las categorías correctas.
    <ul>
      <li>Para **asignación individual**: Ve a **"Productos"**, selecciona el ítem y usa **"Editar Categorías"**.</li>
      <li>Para **asignación masiva**: Usa el **editor masivo** (`bulk editor`), filtra los productos y aplica los cambios.</li>
    </ul>
  </Step>
</Steps>

---

### Cautionary Notes

- **Nombres de Categoría:** Utiliza **nombres descriptivos** y consistentes. Evita los caracteres especiales y los nombres ambiguos para mejorar el SEO y la usabilidad.
- **Jerarquía:** **Limita la profundidad** de la categoría para evitar complejidades en la navegación. Si hay un cambio en el URL, establece un **redirect** (`redirects`) para evitar enlaces rotos.

### Tips for Efficiency

- **Display de Navegación:** Configura las **Opciones de Navegación** (`Navigation`) para añadir categorías clave al menú principal o crear mega menús.
- **Optimización Web:** Asegura el buen rendimiento configurando el **Lazy Loading** y optimizando el tamaño de las **Imágenes de Categoría**.