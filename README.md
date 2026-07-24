# Dynamically Adapting Precision — Europar Slides

[![Build slides](https://github.com/yohanchatelain/Europar-dynamically-adapting-precision/actions/workflows/build-slides.yml/badge.svg)](https://github.com/yohanchatelain/Europar-dynamically-adapting-precision/actions/workflows/build-slides.yml)
[![PDF](https://img.shields.io/badge/slides-PDF-blue)](https://github.com/yohanchatelain/Europar-dynamically-adapting-precision/releases/download/latest-slides/main.pdf)

Source for the Euro-Par presentation slides. The PDF is rebuilt automatically on every push to `main` and published as the `latest-slides` release asset, linked from the badge above.

## Building locally

```bash
cd main
latexmk -pdf -shell-escape main.tex
```
