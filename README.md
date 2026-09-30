# Contexto V7

Juego web Contexto con pistas semánticas adaptativas, modo individual y competitivo.

## Publicación en GitHub + Cloudflare Pages

Este proyecto es estático: no necesita un proceso de build.

### GitHub
1. Crea un repositorio nuevo.
2. Sube `index.html` y este `README.md`.
3. Mantén `index.html` en la raíz del repositorio.

### Cloudflare Pages
1. En Cloudflare, crea un proyecto de Pages conectado al repositorio.
2. Selecciona el repositorio.
3. Como el proyecto es HTML estático, no necesitas framework ni comando de build.
4. Deja el directorio de salida apuntando a la raíz del proyecto.
5. Publica.

Cada cambio enviado al repositorio puede generar un nuevo despliegue.

## IA

El juego no contiene una API key. La integración opcional con un backend de IA utiliza `window.CONTEXTO_AI_ENDPOINT`. Si se conecta un backend, la clave debe permanecer en el servidor y nunca en `index.html`.
