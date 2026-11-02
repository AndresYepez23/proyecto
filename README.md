# C-Dobleta — proyecto de edición TikTok

Proyecto base para reconstruir la edición vertical 9:16 a partir del SRT original. El MP4 de referencia se mantiene separado del audio para montaje posterior en CapCut.

## Estructura prevista
- `src/`: scripts de composición y render.
- `assets/`: recursos visuales ilustrativos.
- `captions/original.srt`: subtítulos originales, sin alterar marcas de tiempo.
- `output/`: render MP4 silencioso.

## Reglas de edición
- Mantener la duración y los tiempos del SRT.
- No representar "Breve pausa" como texto ni como escena especial.
- El MP4 final debe ser silencioso; la narración se agrega desde 00:00 en CapCut.
- Las recreaciones visuales deben identificarse como ilustrativas, no como material documental real.
