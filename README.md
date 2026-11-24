# Invitación XV años · Fryda Sofía

Invitación web de una sola página (HTML, CSS y JavaScript, sin dependencias).

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `xv-fryda`).
2. Sube `index.html` y este `README.md` a la rama `main`.
3. En el repositorio: **Settings → Pages → Build and deployment**.
4. En *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guarda.
5. En uno o dos minutos la página queda en `https://TU-USUARIO.github.io/xv-fryda/`.

## Publicar en Vercel
Importa el repositorio en vercel.com. No necesita configuración: detecta el `index.html` y lo publica.

## Editar los datos
Todo está al inicio del `<script>` de `index.html`, dentro del bloque `CFG`:
nombres, padres, fecha y hora, lugares, itinerario, dress code, número de WhatsApp y música.

- **Hora de la misa y de la recepción:** `places` y `schedule`.
- **Dirección de la misa:** cambia `title` y `where`, y agrega en `map` el nombre del lugar para que aparezca el botón "Ver ubicación".
- **Música propia:** crea la carpeta `audio/`, sube `cancion.mp3` y escribe `audioSrc: "audio/cancion.mp3"`. Si queda vacío suena una melodía de caja musical.
