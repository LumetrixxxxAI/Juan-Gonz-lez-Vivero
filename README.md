# Juan González Vivero — Web

Web de una sola página (one-page) para Juan González Vivero, centro de jardinería y vivero en Alhaurín el Grande (Málaga).

HTML, CSS y JS puros, sin frameworks ni build. Lista para subir tal cual a un hosting estático o a GitHub Pages.

## Estructura

```
index.html
css/style.css
js/main.js
img/            → fotos e iconos (ver pendientes más abajo)
legal/          → aviso legal, privacidad, cookies
robots.txt
sitemap.xml
site.webmanifest
```

## Fotos pendientes

El sitio usa placeholders bien marcados donde faltan fotos reales. Sustituir estos archivos en `img/` (mismo nombre, mismo formato aproximado) y quitar el `.img-placeholder` correspondiente en `index.html` por una etiqueta `<img class="foto-real" src="img/nombre.jpg" alt="...">`:

- `img/hero-vivero.jpg` — foto grande del vivero o de las plantas (hero, portada)
- `img/sobre-nosotros-vivero.jpg` — foto del vivero o del equipo (sección "Sobre nosotros")
- `img/galeria-1.jpg` a `img/galeria-8.jpg` — 8 fotos variadas de plantas, árboles, macetas e interior/exterior del vivero (sección "Galería")
- `img/og-vivero.jpg` — imagen para compartir en redes (Open Graph), 1200×630 px, idealmente una foto potente del vivero

Se recomienda optimizar las fotos para web (formato JPG u WebP, máximo ~300 KB cada una) antes de subirlas.

## Publicar con GitHub Pages

1. Crea un repositorio nuevo en GitHub (puede ser público o privado, GitHub Pages funciona con ambos si tienes plan compatible).
2. Sube este proyecto:
   ```bash
   git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
   git branch -M main
   git push -u origin main
   ```
3. En GitHub, entra en **Settings → Pages**.
4. En "Source", elige la rama `main` y la carpeta `/ (root)`.
5. Guarda. En un par de minutos la web estará disponible en `https://TU-USUARIO.github.io/TU-REPO/`.
6. Si se conecta un dominio propio (por ejemplo `juangonzalezvivero.es`), añádelo en la misma pantalla de Pages y actualiza los DNS del dominio (registro `CNAME` apuntando a `TU-USUARIO.github.io`).
7. Actualiza `index.html`, `robots.txt` y `sitemap.xml` con el dominio final una vez esté decidido (ahora mismo usan `https://juangonzalezvivero.es/` como marcador de posición).

## Notas

- El horario de apertura está pendiente de confirmar — buscar "[a confirmar]" en `index.html` y sustituir por el horario real.
- El teléfono/WhatsApp usado es `952 59 48 36` (`+34952594836`).
- Diseño y desarrollo: **Lumetrix**.
