# Base16Theme Generator

A tool to generate custom Base16 themes. and a collection of custom Base16 themes inspired by nature and the elements.

## Interactive Tools

* **[Theme Creator](https://cheerfulscumbag.github.io/Base16-Theme-Generator/)** - A live tool to design, preview, and export your own custom Base16 color schemes.
* **[Theme Examples](https://cheerfulscumbag.github.io/Base16-Theme-Generator/themes/index.html)** - Browse the collection of pre-made themes with interactive previews.

## How to Use

Every theme lives in its own folder under `docs/themes/<theme-name>/`, which is also the GitHub Pages root:

- `docs/themes/index.html` - the browsable collection (served at `/themes/index.html`)
- `docs/themes/[theme-name]/[theme-name]-dark.yaml` (Base16 Dark Scheme)
- `docs/themes/[theme-name]/[theme-name]-light.yaml` (Base16 Light Scheme)
- `docs/themes/[theme-name]/[theme-name]-preview.html` (Interactive HTML visualizer)

`docs/themes/` is the single source of truth - do not keep duplicate copies of a theme elsewhere, since the published site reads from here directly.

These schemes can be used with any of your favorite applications (terminals, editors, UI elements).