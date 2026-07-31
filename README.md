# Juan González Vivero — Web

Web de una sola página (one-page) para Juan González Vivero, centro de jardinería y vivero en Alhaurín el Grande (Málaga).

HTML, CSS y JS puros, sin frameworks ni build. Lista para subir tal cual a un hosting estático o a GitHub Pages.

## Estructura

```
index.html
css/style.css
js/main.js
img/            → fotos reales del vivero, optimizadas para web
legal/          → aviso legal, privacidad, cookies
robots.txt
sitemap.xml
site.webmanifest
```

## Fotos

Todas las fotos son reales del vivero (procesadas y comprimidas para web, formato JPG):

- `img/hero-vivero.jpg` — entrada del vivero (portada)
- `img/sobre-nosotros-vivero.jpg` — foto de trabajo en el vivero (sección "Sobre nosotros")
- `img/ceramica-1.jpg`, `ceramica-2.jpg`, `ceramica-3.jpg` — sección "Cerámica y decoración"
- `img/galeria-1.jpg` a `img/galeria-8.jpg` — sección "Galería"
- `img/og-vivero.jpg` — imagen para compartir en redes (Open Graph), 1200×630 px

Si en el futuro se quieren sustituir por fotos nuevas o de mayor calidad, basta con reemplazar el archivo correspondiente en `img/` manteniendo el mismo nombre.

## Publicar con GitHub Pages

El repositorio ya está creado y conectado en `https://github.com/LumetrixxxxAI/Juan-Gonz-lez-Vivero` (rama `main`).

1. En GitHub, entra en **Settings → Pages**.
2. En "Source", elige la rama `main` y la carpeta `/ (root)`.
3. Guarda. En un par de minutos la web estará disponible en `https://lumetrixxxxai.github.io/Juan-Gonz-lez-Vivero/`.
4. Si se conecta un dominio propio, añádelo en la misma pantalla de Pages y actualiza los DNS del dominio (registro `CNAME` apuntando a `lumetrixxxxai.github.io`).
5. Actualiza `index.html`, `robots.txt` y `sitemap.xml` con el dominio final una vez esté decidido (ahora mismo usan `https://juangonzalezvivero.es/` como marcador de posición).

## Notas

- El horario de apertura está pendiente de confirmar — buscar "[a confirmar]" en `index.html` y sustituir por el horario real.
- El teléfono/WhatsApp usado es `952 59 48 36` (`+34952594836`).
- Diseño y desarrollo: **Lumetrix**.
