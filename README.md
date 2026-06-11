# Workshop de Dirección de IA

Paquete listo para subir al root de un repositorio en GitHub Pages.

## Archivos

- `index.html`: landing final.
- `favicon.svg`: favicon.
- `og-image.png`: imagen social 1200×630.
- `apple-touch-icon.png`: icono para iOS.

## Antes de publicar

Cuando tengas la URL final, actualiza en `index.html`:

- `canonical`
- `og:url`
- `og:image` con URL absoluta
- `twitter:image` con URL absoluta

Por ahora las imágenes sociales usan rutas relativas para funcionar dentro del mismo root.


## Premios

Los SVG de premios están en el root y el HTML los referencia con rutas relativas:

- `awards_cannes.svg`
- `awards_clio.svg`
- `awards_dad.svg`
- `awards_lia.svg`
- `awards_newyork.svg`
- `awards_ojo.svg`
- `awards_oneshow.svg`


## Hero

La foto principal está en el root como:

- `mike_work.webp`

El HTML la referencia con `./mike_work.webp`.
