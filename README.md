# UTM link generator

A simple, educational UTM builder for the Valpas GTM team. Pick a destination URL, choose a source/medium from curated dropdowns, name your campaign — copy the link.

The generator runs entirely in the browser. No backend, no SDKs, no analytics in the tool itself — PostHog already auto-captures UTM parameters on `$pageview` once the link is clicked, so click-side tracking is free.

## Hosting

Single static file (`index.html`). Deployed via GitHub Pages — push to `main`, then **Settings → Pages → Source: `main` / root**.
