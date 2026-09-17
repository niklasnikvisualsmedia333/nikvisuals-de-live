# NikVisuals live/staging deployment

This repository is intentionally deploy-only. The canonical source code lives in [niklasnikvisualsmedia333/nikvisuals-de](https://github.com/niklasnikvisualsmedia333/nikvisuals-de).

The manual GitHub Actions workflow checks out that public source repository at `main`, builds the root-based noindex staging variant, and publishes only its generated `dist` artifact to GitHub Pages. Do not edit or copy the website source here.
