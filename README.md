# Ontologia-2022-2

#Repositorio para el desarrollo web de la ontología para la materia de FIA 4BM1 siclo escolar 2022-2 ESCOM

Bienvenido al repositorio, aquí encontrarás una ontología sobre el reglamento de tránsito de la CDMX vigente en Abril del 2022.

Esta ontología fué desarrollada a través del software protégé, y su voisualización es posible gracias a la API de webvowl (tambien presente en el repositorio)
Todos los derechos reservados para sus respectivos autores.

Espero te sea de utilidad y no olvides darle una estrella al repositorio si ha sido así (>w<)

Nota: Para lograr le visualización es necesario ya sea, un servidor local como xampp, una extención de vs code, o cualquier servidor local de tu preferencia, esto con el objetivo de evitar el bloqueo por CORS Policy.

# Cómo modificar la api de webVowl para cargar tu propia ontología en vés de la nuestra:

Para que el API cargue por defecto tu propia ontología, sigue esta ruta: ./webvowl/data
Ahí vas a cargar el archivo de tu ontología en formato .json

Posteriormente abre en un editor de texto y carga el archivo de la siguiente ruta: ./webvowl/js/webvowl.app.js

Finalmente busca la línea 8226 y sustituye "tránsito" por el nombre de tu archivo.json que agregaste a la carpeta data.

guardas el archivo y listo, al ejecutar el archivo index(dentro de un servidor local) verás tu ontología cargada por defecto.
