# Optimizador de Tarjetas — PWA v1

Esta versión convierte el HTML original en una Progressive Web App instalable.

## Incluye
- Registro de múltiples tarjetas.
- Fecha de corte y fecha límite de pago.
- Simulación de compra por fecha y monto.
- Calendario mensual con la mejor tarjeta estimada para cada día.
- Ranking por mayor número estimado de días hasta el pago.
- Control opcional de límite y crédito disponible.
- Datos guardados localmente en el dispositivo.
- Exportación/importación JSON.
- Instalación como PWA.
- Funcionamiento offline después de la primera carga.

## Importante para instalarla
Los service workers requieren HTTPS o localhost. Abrir index.html directamente con file:// permite probar la interfaz, pero no activa correctamente la instalación/offline.

Para uso real, sube estos archivos juntos a GitHub Pages, Netlify, Vercel, Cloudflare Pages u otro hosting HTTPS.
