# Entre días · Diario de emociones

Diario del 30 de septiembre al 4 de noviembre de 2026 (36 días). HTML, CSS, JavaScript y Bootstrap 5.3.3 incluido localmente. No requiere instalación, servidor de datos ni cuenta adicional.

## Abrir y llenar
1. Descomprime TODO el ZIP. Abre `index.html` con Chrome o Edge, o publica los archivos en GitHub Pages.
2. Completa los datos de la portada y pulsa **Guardar portada**.
3. Selecciona un día en el calendario. Llena situación, pensamiento, emoción, conducta, idea útil y pensamiento sobre una persona. Agrega lugar y una imagen; el título y pie de foto son opcionales.
4. Pulsa **Guardar día**. Un día completo tiene todos los campos principales y una imagen. Puedes guardar borradores incompletos. Al cambiar de fecha se guardan los cambios pendientes.
5. Descarga un respaldo después de escribir. El JSON incluye los textos, portada y fotos. **Importar** permite recuperarlo en otro dispositivo; reemplaza el diario local, previa confirmación.

## Imprimir o guardar PDF
Pulsa **Imprimir / PDF**. Se guardan los cambios actuales y se prepara una portada con TODOS los días registrados en orden, incluyendo sus imágenes (también los borradores). Los días vacíos no se imprimen.
En el cuadro del navegador elige **Guardar como PDF**, papel A4, escala 100 %, y desactiva encabezados y pies del navegador. También puedes seleccionar tu impresora directamente. Activa gráficos de fondo si quieres conservar todos los colores.
Cada día comienza en una página nueva; textos largos pueden continuar en otra, sin recortarse. La foto conserva sus proporciones. El botón abre la impresión del navegador: no descarga automáticamente un PDF.

## Cómo funciona el guardado
Los datos se guardan en IndexedDB del navegador de ESTE dispositivo y esta dirección. Las fotos se ajustan a un máximo de 1600 px y se convierten a JPEG para ahorrar espacio. Un dibujo puede subirse como fotografía o archivo de imagen.
**Guardar día NO modifica tu repositorio ni sube tus fotos a GitHub.** GitHub Pages aloja la aplicación; los datos permanecen locales. No incluye sincronización automática.
No borres los datos del navegador sin tener respaldo y evita el modo incógnito. Abrir otra dirección, otro navegador o mover la carpeta local puede mostrar un diario vacío: importa tu respaldo para recuperarlo. Para un uso estable es preferible abrir siempre la misma URL de GitHub Pages.

## Publicarlo en GitHub Pages
1. Crea un repositorio y sube el CONTENIDO de esta carpeta: `index.html`, `styles.css`, `app.js`, `vendor/` y `.nojekyll` en la raíz.
2. En Settings > Pages, selecciona Deploy from a branch, rama main y carpeta /(root). Guarda.
3. Abre la dirección que GitHub muestre al finalizar la publicación.
4. Si ya escribiste en la copia local, descarga allí el respaldo e impórtalo en la página publicada.

Puedes guardar manualmente tus respaldos JSON en un repositorio privado como copia, pero la aplicación no los carga automáticamente. No subas respaldos con contenido personal a un repositorio público. No se necesitan tokens en el código.

## Archivos
- index.html: formulario y estructura.
- styles.css: diseño adaptable y formato de impresión.
- app.js: calendario, guardado, fotos, respaldos e impresión.
- vendor/bootstrap.min.css: Bootstrap 5.3.3 (MIT; autores Bootstrap).
- vendor/LICENSE-bootstrap.txt: licencia de Bootstrap.

El diario se entrega vacío para que lo llenes con tus experiencias reales.
