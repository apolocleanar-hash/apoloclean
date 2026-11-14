# ApoloClean — sitio web

Una sola página (`index.html`), sin imágenes ni dependencias: el logo y el bidón están dibujados en vectorial dentro del HTML.

## Subir a GitHub + Cloudflare Pages
1. Creá un repo (ej. `apoloclean-web`) y subí `index.html` en la raíz.
2. Cloudflare → *Workers & Pages* → *Create* → *Pages* → *Connect to Git* → elegí el repo.
   - Framework preset: **None** · Build command: *(vacío)* · Output directory: **/**
3. *Save and Deploy*. Después, en *Custom domains*, agregá `apoloclean.ar`.

## Cambiar datos
- **WhatsApp**: buscá `5491173088740` (aparece varias veces) y el texto visible `11 7308-8740`.
- **Productos y beneficios**: están en el bloque `PRODUCTS` del script, al final del archivo.
- **Presentación** (Bidón 5 L): buscá `5 L` y `bidón 5 L`.
