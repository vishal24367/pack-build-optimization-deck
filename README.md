# Pack Build Optimization — Results Deck

Live deck: **https://vishal24367.github.io/pack-build-optimization-deck/**

A reveal.js presentation summarising the pack/CNB build pipeline optimization work on neeto-deploy.

## Key results
- **29% faster builds** (warm cache): 668 s → 473 s
- **84% smaller `:cache` ECR image**: 3,236 MB → 531 MB
- **95% smaller bundle-install build-gems layer**: 2,652 MB → 125 MB
- Fleet-wide: staging median −41%, production median −27%

## Files
- `index.html` — the deck (open directly or use the GitHub Pages link)

Built with reveal.js 5.1 + Chart.js 4.4 (CDN). Single file, no build step.

Keys: `→` advance · `F` fullscreen · `ESC` overview · `S` speaker notes (if any)
