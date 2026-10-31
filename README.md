# aperturas-ota

Archivos que la app Aperturas lee sin publicar otra versión (un «OTA» pequeño), servidos por GitHub Pages:
`https://carlos-carmona-777.github.io/aperturas-ota/app/<archivo>`.

- `app/config.json`: adónde llegan los reportes de «Ayuda y soporte» (`RemoteConfig` en la app). La app lo pide al
  abrir la hoja de soporte si su copia tiene más de 1 h; un campo que falte se queda con el valor que trae la app.

Para cambiar algo: editar, `git commit` y `git push`. GitHub Pages tarda un minuto en publicarlo y guarda cada archivo
en caché 10 min. **Este repo es público**: nada de correos personales, claves ni datos privados.
