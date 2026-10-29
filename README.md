# LAGGO · Editor de gafetes

Web estática en HTML, CSS y JavaScript. No requiere Node, servidor, compilación ni librerías PDF.

## Publicar en GitHub Pages

1. Descomprime este ZIP.
2. Crea un repositorio en GitHub o abre el repositorio de destino.
3. Sube los archivos extraídos a la raíz del repositorio (no subas el ZIP). index.html debe quedar directamente en la raíz, junto a las dos imágenes.
4. En Settings > Pages > Build and deployment, selecciona Deploy from a branch.
5. Selecciona main (o la rama donde subiste los archivos), carpeta / (root), y pulsa Save.
6. Cuando termine la publicación, abre la dirección que GitHub muestra en Pages.

Documentación: https://docs.github.com/es/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Archivos

- index.html: aplicación completa, editor, lote e impresión.
- plantilla-nitida.png: fondo del gafete.
- diseno-original.png: imagen original usada para conservar el logo sin regeneración.
- .nojekyll: desactiva el procesamiento Jekyll.

Las rutas de imágenes son relativas, compatibles con sitios alojados en una subcarpeta de GitHub Pages.

## Uso

Introduce nombre y puesto, carga una foto y ajusta el encuadre. Agrega el gafete al lote. En Revisa tu lote puedes editar, guardar cambios, cancelar o eliminar cada gafete. Luego usa Imprimir / Guardar PDF y elige Guardar como PDF, escala 100 %, sin márgenes ni encabezados. Medida inicial: 60 × 90 mm, ajustable.

Las fotografías y los datos se procesan localmente en el navegador, no se envían a un servidor. El lote no persiste al recargar o cerrar la página. Esta copia no incluye autenticación de ChatGPT; el acceso depende de la publicación en GitHub Pages.
