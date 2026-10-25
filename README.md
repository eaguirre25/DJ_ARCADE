# ARCADE DJ 90s 🎮🎧

Cabina audiovisual retro con reproductor de YouTube en el centro, personajes pixel art bailando a los costados y dúos de DJ que cambian sin cortar la música.

## Publicar en GitHub Pages
1. Abrir **Settings → Pages** del repositorio.
2. En **Build and deployment**, elegir **Deploy from a branch**.
3. Seleccionar rama **main**, carpeta **/(root)** y guardar.
4. Visitar https://eaguirre25.github.io/DJ_ARCADE/ cuando termine el despliegue.

## Usar
1. Pegar una URL o ID de video de YouTube por línea en **Playlist**.
2. Presionar **Guardar ajustes** y luego **START PARTY**.
3. Usar **Siguiente video**, **Siguiente DJ** o elegir un dúo en la lista.
4. Activar **Pantalla completa** para proyectarlo.

Los enlaces se guardan en el almacenamiento local del navegador. No hay servidor, cuentas ni base de datos. La reproducción incrustada depende de las políticas de YouTube y del navegador. Los DJs cambian por temporizador independiente del reproductor.

## Estructura
- `index.html`: escenario y panel de control.
- `styles.css`: estética arcade, animaciones y adaptación móvil.
- `app.js`: retratos pixel art generados en canvas, roster de DJs, playlist, API de YouTube y configuración.

## Alcance y pendientes
Esta versión implementa el funcionamiento principal, pero **no incluye aún sprites ilustrados individualmente ni sincronización de baile con los BPM reales**. Los retratos generados son aproximaciones caricaturescas de baja resolución, no imágenes fotorrealistas. Las frases del escenario son parodias inventadas. El sitio necesita prueba manual en navegador y configuración de GitHub Pages para estar publicado.

## Créditos
Proyecto audiovisual experimental de fiesta, sin afiliación a YouTube ni a las figuras representadas.