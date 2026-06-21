# pixel-glitch-effect

Interactive LED pixel-matrix flower with a cursor-driven **glitch / Matrix wake**, rendered in WebGL.

Move the mouse over the flower: a short trail behind the cursor displaces individual pixels and turns them into glitching tiles (RGB split, colour scramble, shape warp) or falling Matrix glyphs. Tunable live from the on-screen panel.

![demo](flor-pixel.gif)

## Run

`index.html` is fully self-contained (WebGL + image + fonts inlined). Just open it in a browser, or serve it anywhere.


## Controls (Ajustes del efecto)
- **Área de efecto** — thickness/reach of the wake
- **Píxeles afectados** — how many pixels react
- **Núcleo lleno** — fully-affected core size
- **Matrix ↔ Glitch** — blend between Matrix letters and glitch tiles
- **Intensidad** — displacement strength
- **Tiempo de retorno** — how slowly pixels spring back
- **Hueco tras el cursor** — gap between cursor and the wake
- **Velocidad de parpadeo** — glyph/glitch flicker speed
- **Centelleo de la flor** — ambient twinkle speed

## Files
- `index.html` — standalone build (deploy this)
- `Lotus.dc.html` — editable source component
- `flower_clean.png` — flower texture
