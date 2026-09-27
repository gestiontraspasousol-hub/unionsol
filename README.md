# UnionSol Soluciones Empresariales · Web

Web estática lista para publicar gratis con **GitHub Pages**.

## Publicar (gratis)

1. Crea en GitHub un repositorio **público** llamado `unionsol`.
2. Sube todo el contenido de esta carpeta a la rama `main`.
3. En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)` y **Save**.
4. En uno o dos minutos la web estará en: https://gestiontraspasousol-hub.github.io/unionsol/

Si usas otro nombre de repositorio o de cuenta, cambia la dirección en las etiquetas `og:url`, `og:image`, `canonical` y en `404.html` para que la vista previa de WhatsApp funcione.

## Dominio propio (cuando lo compres)

1. Crea en esta carpeta un archivo llamado `CNAME` con una sola línea: tu dominio (por ejemplo `www.unionsolmadrid.com`).
2. En el proveedor del dominio añade estos registros DNS:
   - `A` para `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` para `www` → `gestiontraspasousol-hub.github.io`
3. En **Settings → Pages** escribe el dominio en **Custom domain** y marca **Enforce HTTPS** cuando aparezca.
4. Cambia la dirección de las etiquetas `og:*` y `canonical` al nuevo dominio.

## Archivos

- `index.html`: la web completa (portada animada del proceso, servicios, cartera, formularios).
- `hi-front.webp`, `hi-shadow.webp`, `mark-160.webp`, `wordmark.webp`: logo en capas y logotipo.
- `favicon.ico`, `favicon-*.png`, `apple-touch-icon.png`, `icon-*.png`, `site.webmanifest`: iconos.
- `og-image.jpg`: imagen que aparece al compartir el enlace (WhatsApp, redes). 1200×630.
