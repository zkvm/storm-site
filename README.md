# storm-site

The $STORM landing page — a single, self-contained static page (`docs/index.html`). It's a React bundle that loads React + PT Mono fonts from CDN, so it needs internet but no build step.

Extracted from the Claude-design "Landing page v4" board.

## Deploy (Netlify)

- **Git-connected:** connect this repo at [app.netlify.com](https://app.netlify.com). `netlify.toml` sets the publish dir to `docs/`, so `docs/index.html` is served at the site root. No build command. Every push auto-redeploys.
- **Instant:** drag the `docs/` folder onto [app.netlify.com/drop](https://app.netlify.com/drop).

## Edit

Change `docs/index.html` and push — Netlify redeploys automatically.
