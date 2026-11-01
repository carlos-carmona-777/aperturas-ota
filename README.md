# aperturas-ota

Archivos que la app Aperturas lee sin publicar otra versión (un «OTA» pequeño), servidos por GitHub Pages:
`https://carlos-carmona-777.github.io/aperturas-ota/app/<archivo>`.

- `app/config.json`: adónde llegan los reportes de «Ayuda y soporte» (`RemoteConfig` en la app). La app lo pide al
  abrir la hoja de soporte si su copia tiene más de 1 h; un campo que falte se queda con el valor que trae la app.

- `app/contenido/`: contenido de las aperturas por OTA (manifiesto y archivos **cifrados**). Lo publica
  `tools/contenido/contenido.py publicar` desde el repo de la app; no se edita a mano.
- `app/noticias.json` y `app/juegos.json`: Novedades y «Mis otros juegos».

Para cambiar algo: editar, `git commit` y `git push`. GitHub Pages tarda un minuto en publicarlo y guarda cada archivo
en caché 10 min. **Este repo es público**: nada de correos personales, claves ni datos privados.

## Derechos

© 2026 Carlos Carmona. Todos los derechos reservados. Estos archivos son solo para la app Aperturas: no se permite
copiarlos ni usarlos en otras apps o productos sin permiso por escrito (ver `LICENSE`).
