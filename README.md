# Swarm Rebuild

**Turn a webpage into an interactive reconstruction canvas, brought to life by an animated swarm of cursors.**

Swarm Rebuild is a standalone JavaScript browser experiment that captures the rendered structure and appearance of the current webpage, then presents it as an interactive visual rebuilding experience.

It can be added to a compatible website with a single `<script>` tag — no browser extension, bundler, framework, or third-party JavaScript dependencies required.

> **Compatibility note:** "Any website" means any website where the script is permitted to run and the page can be inspected by the browser. Content Security Policy (CSP), cross-origin frames, closed Shadow DOM, protected browser pages, and inaccessible media may restrict functionality.

## Features

- **One-file installation** — Load `swarm.js` directly from your own host or a CDN.
- **Automatic startup** — Starts automatically when the script loads.
- **Visual page reconstruction** — Uses DOM and computed-style information to recreate supported page elements.
- **Animated cursor swarm** — Animated cursors, names, and colors bring the reconstruction to life.
- **Interactive tools** — Drawing, pen, ruler, snapping, and duplication interactions.
- **Playback controls** — Replay, build speed, tour, and go-live controls.
- **Sound controls** — Control the experience's sound where supported.
- **Encapsulated interface** — Uses Shadow DOM to minimize CSS conflicts with the host page.
- **JavaScript API** — Start, stop, toggle, and restart the experience programmatically.

## Quick Start

Add the following script tag to a website you own or are authorized to modify:

```html
<script
  src="https://raw.githubusercontent.com/Sheikhlipu123/Swarm-Rebuild-Standalone/main/swarm.js"
  defer
></script>
