# Cotillón 2027 — versión final con tu audio

Esta versión conserva los 3 vídeos, las 14 fotos, el collage animado, los textos nuevos y el botón dorado luminoso. Al sintonizar 2027 reproduce exclusivamente el audio extraído de «WhatsApp Video 2026-10-08 at 23.12.24.mp4», de unos 2 minutos y 30 segundos. No añade la voz ni la música anteriores. No se han añadido las imágenes de ese último vídeo a la web.

## Subir a GitHub, sin organizar carpetas

1. Descarga y descomprime `Cotillon-2027-FINAL-con-tu-audio.zip`. Todos los archivos están sueltos, sin carpetas internas.
2. Abre https://github.com/TopEventosyServicios/COTILL-N-26-27 y entra en **Code**, rama **main**.
3. Pulsa **Add file → Upload files**.
4. Selecciona o arrastra TODOS los archivos que acabas de descomprimir: `index.html`, `README.md`, `audio-2027.mp3`, los 3 vídeos y las 14 fotos. Súbelos en la raíz del repositorio, donde está el `index.html` actual. No subas el ZIP ni una carpeta que envuelva los archivos.
5. Escribe «Cotillón 2027 con audio final» y pulsa **Commit changes** en la rama **main**.
6. Espera a que **Actions → pages build and deployment** termine correctamente.
7. Abre https://topeventosyservicios.github.io/COTILL-N-26-27/ en una ventana privada para comprobar la versión nueva.

Las carpetas antiguas que ya tengas en GitHub pueden quedarse: esta versión usa únicamente los archivos sueltos de la raíz. No tienes que crear, mover ni borrar carpetas. El enlace de vuestra web no cambia.

## Comprobar el resultado

- Pulsa **Activar sonido**, espera a que se prepare el audio y sintoniza **2027**. Las interferencias desaparecen y empieza tu audio desde el principio.
- Los tres vídeos existentes se reproducen en secuencia, sin su sonido original.
- Pulsa **Descubre el cotillón** para ver las 14 fotos del collage.
- Salir de 2027 detiene el audio y devuelve las interferencias. Regresar a 2027 reinicia tu audio.
- **Silenciar sonido** detiene el audio. Activarlo de nuevo lo reinicia si sigues en 2027.
- El audio termina tal como lo has preparado, sin añadir música al final.

El audio se descarga y prepara al abrir la página para que comience al sintonizar cuando esté listo. Si la conexión tarda, la página indica que está preparando el audio y lo inicia automáticamente al terminar la descarga. Si una descarga falla o el navegador interrumpe el sonido, aparece **Reintentar sonido** o **Reactivar sonido**.

## Archivos del paquete

- `index.html`: la web completa.
- `audio-2027.mp3`: tu audio extraído del último vídeo, sin recortes ni cambios de volumen.
- `video-1.mp4`, `video-2.mp4`, `video-3.mp4`: los tres vídeos promocionales.
- `foto-1.jpg` a `foto-14.jpg`: las catorce fotos.
- `README.md`: estas instrucciones.

Para probar el sonido, utiliza la web publicada o un servidor local. Abrir `index.html` por doble clic puede bloquear la carga del audio.
