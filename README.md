# Itinerario · Puerto Rico (18–24 nov 2026)

Página de una sola pantalla para ver el viaje día por día

## Archivos
- `index.html` — la página (diseño, navegación y editor).
- `itinerario.json` — los datos del viaje: vuelos, hoteles, días y actividades.
- `fotos/` — aquí van las fotos. En el editor se escriben como `fotos/nombre.jpg`.

## Publicar en GitHub Pages
1. Sube estos archivos a la raíz del repo `chalvich/TRIP_INTRY`.
2. En el repo ve a **Settings → Pages**.
3. En *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
4. En un par de minutos queda en `https://chalvich.github.io/TRIP_INTRY/`.

## Cómo navegar
- Desliza de lado o usa las flechas ‹ ›.
- El botón del centro abre el **abanico** con todos los días para saltar directo.

## Menú escondido (editar)
- **Mantén presionado el sol** de la portada (≈1 segundo), o
- abre la página con `#editar` al final: `…/TRIP_INTRY/#editar`, o
- en computadora presiona **Shift + E**.

Los cambios se guardan solo en ese dispositivo. Para que se vean en todos lados:
1. Toca **Descargar itinerario.json**.
2. Sube ese archivo al repo reemplazando el anterior (Add file → Upload files).

Si subes fotos desde el editor, quedan incrustadas en el JSON y lo hacen pesado.
Es mejor subirlas a `fotos/` en GitHub y poner la ruta en el editor.
