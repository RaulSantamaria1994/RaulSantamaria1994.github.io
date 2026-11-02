# Raúl Santamaría Domínguez — Portfolio

Portfolio y currículum de desarrollador. Publicado con GitHub Pages en
https://raulsantamaria1994.github.io/

Editar:
- `index.html` — contenido, estilos y scripts (todo en un solo archivo, sin dependencias)
- `raul.jpg` — foto original (se usa al compartir el enlace); `raul-480.*` y `raul-300.webp` son las versiones optimizadas que muestra la web

Para añadir un proyecto, copia uno de los bloques `<article class="project ...">`
de la sección `#proyectos`, cambia textos, etiquetas y enlaces, y actualiza el número (`P—03`).
Los colores están en las variables de `:root` (tema claro y oscuro).

## Chat de la portada
Las respuestas del chat están en el objeto `ANSWERS` del `<script>` final de `index.html`
(texto + tarjetas en HTML). Las palabras clave que llevan a cada respuesta están en `INTENTS`
(en orden de prioridad), y el texto que aparece como pregunta al pulsar un botón, en `LABELS`.
Para añadir un tema: crea una entrada en `ANSWERS`, otra en `INTENTS` y, si quieres, un botón
con `data-ask="clave"`. No hay LLM detrás: es un chat guionizado que funciona en GitHub Pages.

## CV en PDF
`cv/cv.html` es la fuente del CV y `cv/Raul_Santamaria_CV.pdf` el archivo que se descarga desde la web.
Si cambias el CV, abre `cv/cv.html` en Chrome, pulsa Imprimir → "Guardar como PDF"
(tamaño A4, márgenes "Predeterminados") y sustituye `cv/Raul_Santamaria_CV.pdf`.
