# heygen

A [HyperFrames by HeyGen](https://github.com/heygen-com/hyperframes) video composition project.

## Requirements

- Node.js >= 22
- FFmpeg

## Quick start

```bash
npx hyperframes preview   # preview in the browser (live reload)
npx hyperframes lint      # validate the composition
npx hyperframes render    # render to MP4
```

## Project structure

- `index.html` — main composition (root timeline)
- `compositions/` — sub-compositions (referenced via `data-composition-src`)
- `assets/` — media files
- `meta.json` — project metadata
- `hyperframes.json` — HyperFrames CLI config
