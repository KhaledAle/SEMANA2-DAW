# SEMANA2-DAW

Practica de HTML5 semantico y CSS moderno para la Semana 2 de DAW.

## Incluye

- Estructura semantica con `header`, `nav`, `main`, `section`, `article`, `aside` y `footer`.
- Metadatos SEO escritos manualmente, idioma declarado, viewport y enlace de salto.
- Layout hibrido: Grid para las regiones principales y Flexbox para componentes internos.
- Tipografia fluida con `clamp()` y espaciado adaptable con `calc()` y propiedades logicas.
- Responsive design con media queries y Container Queries para las tarjetas.
- Atributos `data-category` y `data-loading` para simular datos de carga XML.

## Validacion y fallback

1. Ejecutar el validador W3C y corregir jerarquia, atributos y cierre de elementos.
2. Revisar contraste, foco visible, navegacion por teclado y nombres accesibles con WAVE.
3. Ejecutar Lighthouse y probar los breakpoints en Chrome, Firefox y Edge.
4. Si `@container` no esta disponible, `@supports not (container-type: inline-size)` conserva una cuadricula de dos columnas.