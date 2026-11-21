# cei-javierdeviana.github.io

Página principal del sitio del **CEI Javier de Viana** (Artigas, Uruguay) en GitHub Pages: `https://cei-javierdeviana.github.io/`.

Este repositorio es especial: como se llama igual que la dirección de la organización, lo que tenga se publica en la raíz del sitio. Los proyectos del CEI viven en sus propios repositorios y se ven en una subcarpeta, por ejemplo [Descubrí Artigas](https://cei-javierdeviana.github.io/descubri-artigas/) (repositorio `descubri-artigas`).

## Para qué sirve

- **Nombre del sitio en Google.** Google muestra un solo nombre arriba de los resultados de toda la dirección `cei-javierdeviana.github.io`, y lo lee de esta página. Los datos estructurados (`WebSite`) de `index.html` le indican que el nombre es «CEI Javier de Viana». Sin esta página, Google mostraba «GitHub Pages documentation».
- **Portada del CEI** con enlace a sus proyectos. Para sumar un proyecto nuevo, copiá el bloque `<a class="project" …>` de `index.html` y cambiá el enlace, la imagen y el texto.
- **`el-proceso/`**: la página «El proceso», con las fotos y los videos de cómo se hicieron las pinturas del CEI (presentación, primera y segunda pintura, invitación y palabras de la docente de Arte). Es la dirección a la que apunta el QR de la pared: `https://cei-javierdeviana.github.io/el-proceso/`. Las fotos están achicadas a 1600 px (y a 640 px en `fotos/th/`) y los videos comprimidos a 720p para que carguen rápido en el celular.
- **`robots.txt`**: solo funciona en la raíz del sitio; le indica a los buscadores dónde están los mapas del sitio (`sitemap.xml` de esta raíz y el de Descubrí Artigas).
- **`404.html`**: la página que se muestra cuando alguien entra a una dirección que no existe.
- **Íconos** (`favicon.ico`, `favicon.svg`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`): la gema que muestran el navegador y Google al lado de cada resultado. Google toma el ícono de esta página para todo el sitio.
- **`google63d47089fb676f9d.html`**: confirma ante Google Search Console que el sitio es del CEI. No hay que borrarlo.

Las visitas se cuentan con Cloudflare Web Analytics, igual que en Descubrí Artigas.
