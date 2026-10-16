# Cámaras de Burgos — prueba técnica

Este repositorio guarda un listado de cámaras extraído de la página municipal y una página de prueba para comprobar si las URL se pueden representar como imágenes.

## Archivos

- `camaras.json`: 11 cámaras con nombre, ID, coordenadas y ruta obtenida en la respuesta de la web.
- `index.html`: prototipo que intenta cargar cada recurso con una etiqueta de imagen y permite abrir la URL original.

## Cómo probarlo

Para que `index.html` pueda leer `camaras.json`, abre el repositorio publicado con GitHub Pages o usa un servidor local estático. Si GitHub Pages está habilitado en Settings → Pages, espera a que termine la publicación y abre la URL que proporciona GitHub.

## Importante

- Las rutas están guardadas tal como se observaron en la respuesta del navegador y pueden cambiar o caducar.
- La URL de un documento no demuestra que sea una API de vídeo en directo: puede devolver una captura fija o un archivo adjunto.
- El estado de carga del navegador solo indica si la respuesta se puede mostrar como imagen; no verifica actualización en vivo.
- Todavía no se ha implementado IA, seguimiento de autobuses ni avisos por Telegram.
- No hay tokens, contraseñas ni credenciales en estos archivos.
