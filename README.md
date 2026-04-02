# lecturasaludable

Sitio web estatico de Lectura Saludable, orientado a promocionar talleres, libros, biblioteca, metodo R.I.E. y servicios editoriales personalizados.

## Contenido

- `index.html`: landing principal.
- `cambios.html`, `test.html`: paginas auxiliares de prueba o soporte.
- `hero.mp4`, `fondo.mp4`, imagenes de libros y portadas: assets principales.
- `CNAME`, `sitemap.xml`, `site.webmanifest`: soporte de publicacion y SEO.

## Secciones principales

- nuevo lanzamiento editorial
- talleres y grupos
- momentos especiales y libros personalizados
- catalogo de libros
- biblioteca saludable
- metodo R.I.E.
- sobre la autora y redes sociales

## Stack

- HTML estatico
- CSS embebido
- JavaScript vanilla
- Assets locales para video e imagenes

No hay build ni dependencias.

## Verlo localmente

```bash
cd lecturasaludable
python3 -m http.server 8000
```

Abrir `http://localhost:8000`.

## Deploy

Publicacion estatica simple. Mantener:

- `CNAME`
- assets multimedia en la raiz
- `sitemap.xml` y manifest

## Notas

- El sitio tiene bastante contenido editorial dentro del HTML principal; si sigue creciendo, conviene separar secciones en paginas o datos externos.
