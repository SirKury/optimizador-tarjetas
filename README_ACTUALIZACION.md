# Optimizador de Tarjetas — actualización PWA v1.1

Esta carpeta contiene únicamente los archivos que deben reemplazarse en el repositorio actual:

- `index.html`
- `service-worker.js`

No reemplaces el `manifest.webmanifest` ni los iconos; los actuales siguen siendo compatibles.

## Cambios v1.1

- Diseño mobile-first tipo aplicación.
- Navegación inferior: Inicio / Tarjetas / Simular / Calendario.
- Pantalla inicial: "¿Qué tarjeta uso hoy?"
- Ranking automático diario.
- Resumen de tarjetas, días máximos y crédito disponible.
- Simulador responsive.
- Calendario mensual táctil.
- Vista de detalle al tocar un día.
- Mantiene la clave de almacenamiento de v1, por lo que las tarjetas guardadas en el navegador no se pierden.
- Service Worker v1.1 para actualizar correctamente la PWA y seguir funcionando offline.

## Publicación en GitHub

En la raíz de `SirKury/optimizador-tarjetas`, usa **Add file > Upload files** y sube `index.html` y `service-worker.js`.
GitHub reemplazará los archivos existentes. Confirma con **Commit changes**.
El workflow de GitHub Pages volverá a desplegar la app automáticamente.
