# Páginas públicas de Five Stack

Lo que se publica en <https://fivestackgames.github.io/>.

| Página | Dirección | De dónde sale |
|---|---|---|
| Política de privacidad de Darkward | <https://fivestackgames.github.io/darkward/privacidad/> | `docs/politica-de-privacidad.md` del repositorio del juego (privado) |

## Cómo se cambia

1. Primero se cambia `docs/politica-de-privacidad.md` en el repositorio del juego. **Ese texto manda.**
2. Después se pasa el cambio a `darkward/privacidad/index.html`, en los tres idiomas, y se actualiza la
   fecha de «Última actualización».
3. Todo por Pull Request, nunca directo a `main`.

GitHub Pages publica `main` solo, en uno o dos minutos.

La dirección de la política está cargada en Play Console y en el botón Privacidad de los ajustes del
juego: **no se mueve el archivo de lugar**.

Las páginas no cargan nada de afuera (fuentes, scripts, imágenes): la política de privacidad no puede
pasarle datos a nadie.
