# MT-001 · Diagnóstico y mantenimiento de equipos

Ficha técnica interactiva (HTML + CSS + JS puro, sin dependencias) para el diagnóstico y mantenimiento de equipos de cómputo – JALS Soporte Técnico.

- Los cambios se guardan automáticamente en el navegador (`localStorage`).
- Botón **Imprimir / guardar PDF** para exportar la ficha.

## Estructura

```
index.html
assets/logo.png
vercel.json
.nojekyll
```

## Publicar en GitHub Pages

1. Sube el repositorio a GitHub.
2. Settings → Pages → Source: `Deploy from a branch` → rama `main`, carpeta `/ (root)`.

## Publicar en Vercel

1. En [vercel.com/new](https://vercel.com/new) importa el repositorio de GitHub.
2. Framework Preset: **Other**. Build Command y Output Directory: déjalos vacíos.
3. Deploy.
