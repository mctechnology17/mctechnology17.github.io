# MC Technology · mctechnology17.github.io

Página de enlaces de MC Technology: redes, donaciones, códigos de descuento y contacto.
Se publica con GitHub Pages desde la rama `master` en https://mctechnology17.com (archivo `CNAME`).

## Estructura

| Archivo | Qué es |
|---|---|
| `index.html` | La página (HTML, CSS y JS en un solo archivo) |
| `_data/descuentos.yml` | Códigos de descuento: añade una entrada y aparece sola |
| `assets/brand/` | Logo, isotipo, favicon, fondo, avatar, imagen para redes (OG) |
| `assets/fonts/` | Poppins (local, sin Google Fonts) |
| `privacidad.html`, `condiciones.html` | Política de privacidad y condiciones (`/privacidad/`, `/condiciones/`); las piden Google, Meta y TikTok para las apps de publicación |
| `404.html` | Página de error |

## Probar en local

```sh
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve
# http://127.0.0.1:4000
```

Todo lo que se sube a `master` es público.
