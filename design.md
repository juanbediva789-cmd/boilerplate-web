# Especificación de Diseño Estético

## 1. Filosofía de Diseño
Diseño minimalista inspirado en plataformas de referencia como Apple.com, enfocado en el contenido, espacios limpios y legibilidad alta.

## 2. Paleta de Colores
- **Color Principal (Dark):** `#1d1d1f` - Aplicado en textos contrastados y footer.
- **Color Secundario / Acción:** `#0066cc` - Para botones principales y enlaces activos.
- **Fondo General:** `#f5f5f7` - Gris suave para menor fatiga visual.
- **Contenedores:** `#ffffff` - Blanco puro para dar jerarquía a las tarjetas y contenido principal.

## 3. Tipografía
- **Fuente principal:** `Roboto` integrada desde Google Fonts.
- **Jerarquía:**
  - Títulos principales (h1/h2): Peso Bold (700).
  - Subtítulos (h3): Peso Regular (400).
  - Cuerpo de texto: Peso Light/Regular (300/400).

## 4. Layout y Estructura
- **Ancho del sitio:** Dinámico entre `1000px` y `2000px` mediante `min-width` y `max-width`.
- **Flexbox:** Empleado en cabecera, estructura principal (contenido vs sidebar), tarjetas de artículos y pie de página.
- **Elemento fijo:** Botón flotante anclado en `position: fixed` a 24px del borde inferior derecho.