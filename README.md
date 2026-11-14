# Spam Buffer (experimental)

> Versión modificada: logo cambiado y mensaje en pantalla eliminado. El mod original es de C5least.

Asistencia de spam dentro del juego para Geometry Dash, hecho como mod de [Geode](https://geode-sdk.org).

- **ID:** `c5least.spam-buffer`
- **Versión:** v1.0.0-beta
- **Desarrollador:** C5least
- **Geode:** 5.11.2
- **Geometry Dash:** 2.2081 (Windows, Android, macOS, iOS)

## Instalación

1. Descarga `c5least.spam-buffer.geode` desde la sección **Releases** de este repositorio.
2. Cópialo a la carpeta `geode/mods` de tu Geometry Dash (en Android, por el instalador de Geode o a mano en esa carpeta).
3. Abre el juego.

## Contenido del repo

- `mod.json`: metadatos del mod (los mismos que lleva el `.geode`).
- `logo.png`: logo del mod.
- `releases/c5least.spam-buffer.geode`: el mod compilado para Windows, macOS, Android 32/64 e iOS.

Este repositorio solo distribuye el mod ya compilado. El código fuente es de C5least y no está incluido aquí.

## Publicar una nueva versión

Sube el nuevo `.geode` a `releases/`, haz commit y crea una etiqueta (`git tag v1.0.1 && git push --tags`). El workflow de `.github/workflows/release.yml` crea la Release y adjunta el archivo.
