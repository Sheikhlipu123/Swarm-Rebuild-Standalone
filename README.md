# Swarm Rebuild

**Turn a webpage into an interactive reconstruction canvas, brought to life by an animated swarm of cursors.**

Swarm Rebuild is a standalone JavaScript browser experiment that captures the rendered structure and appearance of the current page, then presents it as a visual rebuilding experience. It can be added to a compatible website with a single `<script>` tag—no browser extension, bundler, framework, or third-party JavaScript dependency is required.

> **Compatibility note:** “Any website” means any website where the script is permitted to run and the page can be inspected by the browser. Content Security Policy, cross-origin frames, closed Shadow DOM, protected browser pages, and inaccessible media can restrict functionality.

## Features

- **One-file installation** — load `swarm.js` directly from your own host or a CDN.
- **Automatic startup** — starts when the script loads by default.
- **Visual page reconstruction** — uses DOM and computed-style information to recreate supported page elements.
- **Animated cursor swarm** — animated cursors, names, and colors bring the reconstruction to life.
- **Interactive tools** — drawing, pen, ruler, snapping, and duplication interactions.
- **Playback controls** — replay, build speed, tour, and go-live controls.
- **Sound controls** — control the experience's sound where supported.
- **Encapsulated interface** — the Swarm interface uses Shadow DOM to reduce CSS conflicts with the host page.
- **JavaScript API** — start, stop, toggle, and restart the experience programmatically.

## Quick start

Add this script tag to a page you own or are authorized to modify:

```html
<script src="https://raw.githubusercontent.com/Sheikhlipu123/Swarm-Rebuild-Standalone/refs/heads/main/swarm.js" defer></script>
```

The experience starts automatically after the page is ready. Replace `https://YOUR-HOST/swarm.js` with the URL where you host the file.

### Test locally

Place `swarm.js` beside an HTML file and add:

```html
<script src="./swarm.js" defer></script>
```

Open the page through a local web server for the most representative browser behavior. Some browser features may behave differently when a page is opened directly using a `file://` URL.
