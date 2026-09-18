# alberto-del-amo-web

Web estatica preparada para Cloudflare Pages.

Archivos clave:

- `index.html`: pagina principal.
- `Alberto-del-Amo-CV.pdf`: PDF que se abre con el boton "Ver CV".
- `descargar-cv.pdf`: copia del mismo PDF para el boton "Descargar CV".
- `linkedin-preview.png`: imagen social para que LinkedIn reconozca el enlace en destacados y publicaciones.
- `_headers`: regla de Cloudflare Pages para forzar la descarga de `descargar-cv.pdf`.

En Cloudflare Pages no hace falta comando de build. La carpeta de salida es la raiz del repositorio.

## Propuesta Albali
Se incluye `propuesta-albali.pdf` para visualización directa en navegador.

URL prevista tras desplegar en Cloudflare Pages:
`https://alberto-del-amo.pages.dev/propuesta-albali.pdf`

