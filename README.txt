MAPA DE CUENTAS — PWA

Corrección: al importar CSV ya no hace falta que tenga columnas lat/lon. Si faltan, la app ubica cada cuenta con coordenadas aproximadas del mapa web original, primero por provincia + ciudad y, si no hay coincidencia, por provincia. Es una referencia geográfica, no la ubicación exacta del domicilio.

PUBLICAR EN GITHUB PAGES
1. Descomprimí el ZIP.
2. En el repositorio mapa-cuentas, entrá a la carpeta raíz.
3. Subí/reemplazá index.html y README.txt; mantené manifest.webmanifest, sw.js e icons/.
4. Hacé Commit changes y esperá que Actions termine en verde.
5. Abrí el sitio y recargá. Si sigue apareciendo la versión anterior, cerrá la pestaña y abrí una ventana incógnito nueva.

Los datos importados quedan guardados localmente en el dispositivo. No cargues información confidencial en una URL pública.
