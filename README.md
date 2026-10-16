# Base16Theme Generator

A tool to generate custom Base16 themes. and a collection of custom Base16 themes inspired by nature and the elements.

## Interactive Tools

* **[Theme Creator](https://cheerfulscumbag.github.io/Base16-Theme-Generator/)** - A live tool to design, preview, and export your own custom Base16 color schemes.
* **[Theme Examples](https://cheerfulscumbag.github.io/Base16-Theme-Generator/themes/index.html)** - Browse the collection of pre-made themes with interactive previews.

## How to Use

Every theme lives in its own folder in the repository root, which is also the GitHub Pages site:

- `index.html` - the theme creator (served at `/`)
- `themes/index.html` - the browsable collection (served at `/themes/index.html`)
- `[theme-name]/[theme-name]-dark.yaml` (Base16 Dark Scheme)
- `[theme-name]/[theme-name]-light.yaml` (Base16 Light Scheme)
- `[theme-name]/[theme-name]-preview.html` (Interactive HTML visualizer)

GitHub Pages publishes from the repository root (`main` / `(root)`). The theme folders are the single source of truth, so do not keep duplicate copies under `docs/`.

These schemes can be used with any of your favorite applications (terminals, editors, UI elements).