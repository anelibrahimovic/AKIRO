# Quiet Ascent

A minimal, cozy illustrated place to pause. All three landscape illustrations and the hero are original SVGs embedded in the page, using paper-texture and watercolor-style washes. No external image assets or build tools required.

## Experience

- Illustrated home page and three explorable scenes: The Hidden Path, A Window A While, The Softer Shore.
- Optional locally synthesized soft wind-like ambience (click Sound Off to enable; requires user gesture).
- Breath pacing: 4 seconds inhale, 4 seconds hold, 6 seconds exhale. Reset at any time.
- Scene-specific 5, 15, or 25-minute focus timer.
- A journal with browser-local saving and optional plain-text export. It is not synced across devices. Clearing browser storage removes saved writing.
- Mobile navigation, semantic controls, dialog with native focus handling, keyboard support, and reduced-motion consideration.

## Run

Open `index.html` directly in a modern browser or serve locally with `python3 -m http.server 8000` in this directory and open localhost:8000.

## Publish

This folder is isolated from any existing project. Move its contents to the root of a dedicated repository for GitHub Pages, or publish from a matching configured Pages source. GitHub Pages deployment is not automatically enabled by this change.

## Design

Palette: muted olive, ecru, charcoal, warm taupe. Typeface: Italiana for display headings with a serif fallback; DM Sans for navigation and body with a sans fallback. Fonts are externally loaded from Google Fonts, but the page remains usable without them.
