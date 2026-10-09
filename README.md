# Cotillón 2027 — audio corregido

Conserva los tres vídeos promocionales, las catorce fotos, el collage animado y todos los cambios de textos y botón. Utiliza únicamente el audio del vídeo que aportaste, sin mezclar ninguna música anterior.

El audio se ha preparado de nuevo desde el vídeo original: se han corregido los niveles excesivos antes de convertirlo a MP3 y se ha equilibrado el volumen con control de picos. Mantiene la duración completa, unos 2 minutos y 30 segundos.

## Actualizar la web que ya has publicado

1. Descarga y descomprime `Cotillon-2027-AUDIO-CORREGIDO.zip`. Los archivos están sueltos, sin carpetas internas.
2. Abre https://github.com/TopEventosyServicios/COTILL-N-26-27, en **Code → main**.
3. Pulsa **Add file → Upload files**.
4. De este ZIP, sube `index.html` y `audio-2027-corregido.mp3` en la raíz del repositorio, donde está el `index.html` actual.
5. Pulsa **Commit changes**, guardando en `main`.
6. Espera a que **Actions → pages build and deployment** termine correctamente.
7. Abre https://topeventosyservicios.github.io/COTILL-N-26-27/ en una ventana privada. Pulsa **Activar sonido** y sintoniza **2027**.
8. Comprueba el resultado en el iPhone con el volumen a un nivel medio, por ejemplo al 50–60 %.

La versión anterior de audio puede quedarse en el repositorio: la web usa el archivo con el nuevo nombre, para evitar que se reproduzca una copia antigua guardada por el navegador. El enlace de la web sigue siendo el mismo.

## Publicar todo desde cero

Este ZIP también incluye `README.md`, los tres vídeos y las catorce fotos. Si necesitas subir el paquete completo, selecciona todos los archivos sueltos y súbelos en la raíz del repositorio.

## Comportamiento

El audio se precarga y se activa tras pulsar **Activar sonido**. Sintonizar 2027 elimina las interferencias e inicia el audio. Salir de 2027 lo detiene; volver a 2027 lo reinicia. Los vídeos siguen sin su audio original. El audio termina sin añadir otra música.

Si la conexión tarda en descargar el audio, aparece el estado de preparación y comienza automáticamente cuando está listo. Los botones **Reintentar sonido** y **Reactivar sonido** permiten recuperar una descarga fallida o una interrupción del navegador.

La web solicita el modo de reproducción de medios en los navegadores que lo admiten. El volumen físico del iPhone sigue siendo el que elijas con sus botones.
