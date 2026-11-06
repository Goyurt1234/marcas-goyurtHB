# Marcas Goyurt

Formulario para registrar marcas de ingreso y salida (cédula, día, punto, hora, tipo y comentario) y descargar el plano de carga masiva para GeoVictoria (Hoja1: CC, Fecha, Hora, Tipo, Centro de Costo, Comentario).

Todo funciona en el navegador: no hay servidor ni base de datos. Las marcas quedan guardadas solo en el navegador de quien las registra hasta que descarga el plano. No se pueden cargar días posteriores a hoy.

## Publicar con GitHub Pages

1. En GitHub, crea un repositorio nuevo **público** (por ejemplo `marcas-goyurt`).
2. Sube `index.html` y este `README.md` con **Add file → Upload files** y luego **Commit changes**.
3. Ve a **Settings → Pages**. En *Build and deployment* elige **Deploy from a branch**, rama **main**, carpeta **/ (root)** y pulsa **Save**.
4. En uno o dos minutos la página queda en `https://TU-USUARIO.github.io/marcas-goyurt/`.

## Actualizar la lista de tiendas

Busca `const PUNTOS = [` en `index.html` y agrega o quita tiendas con el mismo formato (`"214 NUEVA TIENDA"`). Guarda y vuelve a subir el archivo.
