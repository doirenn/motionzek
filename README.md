# Motionzek

Sitio de Germán Carrillo (Motionzek), editor de video y motion graphics remoto. Hay dos páginas: `index.html` (inglés) y `es-index.html` (español).

## Conectar el dominio

1. Busca en todo el proyecto el texto `https://DOMINIO-DEL-CLIENTE.com` y reemplázalo por el dominio real, con `https://` y sin barra final.
2. No cambies lo que va después de ese texto. La página en inglés queda en la raíz (`/`) y la página en español queda en `/es-index.html`.
3. Revisa que `URL_SITIO_EN` y `URL_SITIO_ES`, al final de cada HTML, coincidan con el canonical, el hreflang, Open Graph, el JSON-LD, `sitemap.xml`, `robots.txt` y `llms.txt`.
4. Sube a la raíz del hosting: `index.html`, `es-index.html`, `og-image.jpg`, `robots.txt`, `sitemap.xml` y `llms.txt`.
5. No subas `portafolio_web_motionzek.html`. Es un borrador anterior y lleva `noindex`.
6. En el DNS, apunta el dominio al hosting. Cuando responda, abre `/` y `/es-index.html` y prueba el cambio de idioma y un botón de WhatsApp.
7. En Google Search Console, agrega la propiedad y envía `sitemap.xml`.

## Publicar

Sirve los archivos como sitio estático. `index.html` debe abrirse al entrar al dominio. No hace falta compilar nada: los estilos cargan desde el CDN de Tailwind.

La imagen para redes es `og-image.jpg` (1280 x 720). El favicon actual es un ícono temporal dentro del HTML. Cuando haya logo, se puede sustituir.
