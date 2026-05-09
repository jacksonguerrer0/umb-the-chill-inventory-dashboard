# Dashboard de inventario - The Chill

Este proyecto es un dashboard administrativo para controlar el inventario de **The Chill**. La propuesta está pensada como una pantalla real de gestión: sobria, clara, responsive y enfocada en decisiones operativas.

## Objetivo

El dashboard permite revisar el estado del inventario antes del cierre o durante una revisión física del local. La idea es identificar rápido:

- Insumos críticos.
- Productos cercanos al mínimo.
- Productos estables.
- Próximos vencimientos.
- Prioridades de compra o reposición.
- Consumo aproximado por categoría.

## Tecnologías usadas

- HTML5 semántico.
- CSS3.
- CSS Grid para el layout principal.
- Flexbox para componentes internos.
- Variables CSS.
- Media queries para escritorio, tablet y móvil.
- Estados `:hover` y `:focus-visible`.
- Roles ARIA y buenas prácticas básicas de accesibilidad.

## Diseño

El diseño se ajustó a una estética de dashboard administrativo real: fondo claro, tarjetas blancas, sidebar oscuro, tipografía limpia y uso limitado de colores. Los colores fuertes se dejaron únicamente para estados importantes como crítico, reponer o bien.

Se tomó como referencia visual general el estilo de dashboards modernos de inventario y administración: sidebar lateral, encabezado superior, tarjetas de resumen, tabla central y panel de acciones.

## Estructura del proyecto

```text
the_chill_inventory_dashboard/
├── index.html
├── styles.css
├── assets/
│   ├── logo.png
└── evidencias/
    └── README.md
```

## Responsividad

El proyecto tiene tres comportamientos principales:

### Escritorio

- Sidebar fijo a la izquierda.
- Header superior.
- Tarjetas en cuatro columnas.
- Tabla amplia y panel lateral de prioridades.

### Tablet

- Sidebar más compacto.
- Tarjetas en dos columnas.
- Secciones principales en una sola columna para mejorar lectura.

### Móvil

- Sidebar oculto tipo menú lateral.
- Botón para abrir el menú.
- Tarjetas apiladas.
- Tabla convertida en tarjetas verticales para que no dependa solo del scroll horizontal.
- Botones y buscador adaptados al ancho de pantalla.

## Accesibilidad

El proyecto incluye:

- Enlace para saltar al contenido principal.
- Uso de etiquetas semánticas: `header`, `main`, `aside`, `section`, `article` y `footer`.
- Roles ARIA en navegación, contenido principal y footer.
- Texto alternativo en el logo.
- Estados visibles de foco para navegación con teclado.
- Tabla con `caption`.
- Contraste sobrio entre texto, fondo y estados.

## Cómo ejecutar

Solo abre el archivo `index.html` en el navegador.

También puedes usar **Live Server** en Visual Studio Code.
