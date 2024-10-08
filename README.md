# JupyterLite Demo

[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://quansight.github.io/jupyterlite-demo/)

JupyterLite deployed as a static site to GitHub Pages, for demo purposes.

## Try it in your browser

- https://quansight.github.io/jupyterlite-demo/
- https://quansight.github.io/jupyterlite-demo/files/demo.html

## Requirements

JupyterLite is being tested against modern web browsers:

- Firefox 90+
- Chromium 89+

## Developing locally:

```
pip install -r requirements.txt
jupyter lite build --contents content && jupyter lite serve
open http://127.0.0.1:8000/files/demo-dev.html
```
