# Publicar el portafolio con GitHub Pages y Google

## Publicación

1. Abre [Settings → Pages](https://github.com/rodolfo99/rodolfo99/settings/pages) del repositorio **rodolfo99/rodolfo99**.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Selecciona la rama **main** y la carpeta **/docs**. Guarda los cambios.
4. Confirma en la propia pantalla de Pages que aparece un despliegue correcto y visita **https://rodolfo99.github.io/rodolfo99/**. Si no aparece, revisa la pestaña **Actions**. Que estos archivos estén en main **no significa** que Pages se haya habilitado automáticamente.

> La ruta canonical, sitemap y robots fueron preparados para un sitio de proyecto (/rodolfo99/), no para la raíz de un repositorio de usuario llamado rodolfo99.github.io.

## Google Search Console

1. Ve a https://search.google.com/search-console/ y agrega la propiedad de prefijo URL `https://rodolfo99.github.io/rodolfo99/`.
2. Verifica la propiedad mediante el método que Google ofrezca. Si pide archivo HTML, súbelo a `docs/` mediante GitHub y vuelve a comprobar.
3. En **Sitemaps**, envía `https://rodolfo99.github.io/rodolfo99/sitemap.xml`.
4. Con **Inspección de URLs**, solicita indexación de la página principal después de verificar que responde HTTP 200. La indexación no es inmediata ni está garantizada.
5. Comprueba en Google mediante `site:rodolfo99.github.io/rodolfo99` (orientativo, no exhaustivo). Analiza resultados reales en Search Console.

## Otros pasos

- Desde tu perfil GitHub, agrega `https://rodolfo99.github.io/rodolfo99/` como **Website** en **Edit profile**.
- Publica ese enlace en tu currículum y otros perfiles profesionales legítimos.
- Mantén descripciones cortas y temas relevantes en los repositorios. Evita rellenar con palabras clave y evita prometer resultados en Google.
- El archivo `robots.txt` ubicado en `docs/` se publicará en la ruta **/rodolfo99/robots.txt**, no en la raíz del dominio; Google interpreta robots.txt solo en raíz. Aquí es un recurso informativo y no asegura reglas de rastreo a nivel de dominio.

## Mantenimiento

- Edita `docs/index.html` para cambiar la descripción y proyectos.
- Edita `docs/styles.css` para modificar el diseño.
- Cuando el sitio ya esté disponible y los contenidos hayan sido verificados, mantén los enlaces y los metadatos actualizados.
