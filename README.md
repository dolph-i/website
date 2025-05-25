# MATRACO Website

Dieses Repository enthält den Quellcode für die neue statische Website **matraco.de** auf Basis von **Jekyll** + **Tailwind CSS**.

## Quick Start (Entwicklung)

```bash
bundle install
bundle exec jekyll serve
```

Die Seite ist dann unter <http://localhost:4000> erreichbar.

## Deployment auf GitHub Pages

1. Aktiviere *GitHub Pages* in den Repository‑Einstellungen (`main` Branch, `/` Root).  
2. (Optional) Lege in der Repository‑Root eine Datei **CNAME** mit dem Inhalt `matraco.de` an, um die Domain aufzuschalten.

## Ordnerstruktur

```
_config.yml
_layouts/          # Templates
pages/             # Markdown-Seiten (Impressum, Datenschutz …)
index.md           # Startseite
```

Änderungen können einfach in den Markdown‑Dateien vorgenommen werden.