# Web Nutrición Oncológica — #TratamientoCompleto

Sitio estático (sin build).

- `index.html` — página principal
- `support.js`, `image-slot.js` — runtime
- `assets/` — imágenes

## Deploy
1. Subir todo el contenido de esta carpeta a la raíz del repo de GitHub.
2. En Netlify: Add new site → Import from Git → elegir el repo.
3. Build command: vacío · Publish directory: `.` (ya está en `netlify.toml`).

Cada push a GitHub redeploya automáticamente.

Los resultados en vivo leen el Google Sheet público cada 5 s; el Sheet debe seguir compartido como "Cualquier persona con el enlace puede ver".
