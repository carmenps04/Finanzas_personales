# Finanzas Personales

App web para registrar ingresos y gastos, clasificarlos por categorías y consultar el resumen mensual y anual con gráficos. Los movimientos se pueden exportar a CSV.

Enlace: https://carmenps04.github.io/mi-primera-app/

## Uso

- Se abre en el navegador y se puede instalar en el móvil como aplicación (PWA): en el iPhone, Safari → Compartir → «Añadir a pantalla de inicio».
- Cada usuario inicia sesión y sus datos se guardan en Firebase (Firestore).

## Cómo está hecha

La he desarrollado con Claude Code. Yo he decidido qué debía hacer la app y cómo se usa, he probado cada versión y he pedido los cambios. El código lo ha generado la IA.

- HTML, CSS y JavaScript en un solo archivo (`index.html`).
- Firebase Authentication y Firestore para usuarios y datos (`firestore.rules`).
- `manifest.json` y `sw.js` para instalarla en el móvil.
- Publicada en GitHub Pages.
