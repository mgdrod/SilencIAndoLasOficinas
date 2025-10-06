# SilencIAndo las oficinas — sitio estático
Paquete listo para publicar en **GitHub Pages**.

## Estructura
- `index.html` — página principal.
- `404.html` — página de error para enlaces rotos.
- `.nojekyll` — desactiva el procesado de Jekyll en GitHub Pages.

## Cómo publicarlo
1. Crea (o abre) un repositorio en GitHub.
2. Sube estos archivos a la **raíz** del repositorio.
3. Ve a **Settings → Pages**:
   - *Source*: **Deploy from a branch**
   - *Branch*: `main` (o `master`) y **/ (root)**
   - Guarda cambios.
4. En ~1 minuto verás el enlace del sitio: `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`

### URL sin `/NOMBRE_DEL_REPO/` (opcional)
Crea un repo llamado `TU_USUARIO.github.io` y sube los archivos a su raíz.

### Dominio propio (opcional)
Añade un archivo `CNAME` con tu dominio (p. ej. `www.midominio.com`) y configura DNS según la guía de GitHub Pages.
