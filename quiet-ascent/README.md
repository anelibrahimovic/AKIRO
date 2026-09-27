# Quiet Ascent — Focus Room

A dark, minimalist, cozy focus room. Rather than a word-heavy digital sanctuary, this is a functional one-page tool to set one intention, start a focus timer, and keep a short task list.

## Features
- 25-minute focus, 5-minute break and 50-minute deep-work timers with pause, resume and reset.
- Daily completed-session/minute counters, persisted in browser localStorage.
- One current focus intention and a checklist of up to 20 tasks, saved locally.
- Optional browser-generated ambience that starts only on user interaction.
- Responsive mobile and desktop layout, keyboard-friendly controls, reduced-motion support.

## Artwork
The featured artwork is an optimized crop **of the exact reference image supplied in the conversation**, used to match the requested illustrated aesthetic in this prototype. **Before publishing publicly or commercially, confirm that you own or have permission to republish this artwork.** Otherwise replace `assets/watercolor.webp` with licensed/commissioned art matching the muted architectural-watercolor style.

## Run
From inside `quiet-ascent`: `python -m http.server 8000`, then open localhost:8000.

This is a static HTML/CSS/JavaScript project, no build dependencies. Your data stays on the browser/device and is lost if you clear browser storage. Google Fonts are optional; fallback fonts work offline. GitHub Pages is not automatically enabled.