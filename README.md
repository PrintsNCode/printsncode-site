# Web de PrintsNCode

Repositorio privado de la portada y la página de enlaces de https://printsncode.com/.

- `index.html`: portada.
- `link/index.html`: página de enlaces.
- `CNAME`: dominio `printsncode.com`.

El editor público está en https://github.com/PrintsNCode/printsncode-web y el conversor en https://github.com/PrintsNCode/universal-gcode-converter.

## Publicación con GitHub Pages

GitHub Pages debe publicar la rama `main` y la carpeta raíz `/`. El repositorio permanece privado, mientras la web y los recursos enviados al navegador son públicos. Publicar Pages desde un repositorio privado de una cuenta personal requiere un plan de GitHub compatible, como GitHub Pro.

Cloudflare se utiliza para el DNS: los CNAME del dominio raíz y `www` apuntan a `printsncode.github.io`. Configura el dominio personalizado `printsncode.com` en Pages y activa HTTPS obligatorio cuando GitHub lo permita.

Para actualizar, exporta ambas páginas desde el editor, sustituye los dos HTML respetando estas rutas y guarda los cambios en `main`. Con Pages habilitado, GitHub construye y publica esa rama.

No se incluyen el editor personal, proyectos JSON privados ni fotografías de origen. La privacidad del repositorio no oculta el contenido de las páginas servidas públicamente.
