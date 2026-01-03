# Snakes & Ladders 3D (PWA)

A fast, modern Snakes & Ladders game built as a Progressive Web App (PWA), featuring smooth 3D dice, smart six-roll rules, and offline play against friends or AI.

## Features

- 3D dice cube with realistic roll animation
- Classic 2‑player mode and vs AI mode
- Fair six‑roll rules with third‑six penalty
- Animated snakes and ladders movement
- Offline support via service worker
- Mobile‑first portrait layout with desktop landscape support

## Tech Stack

- HTML5, CSS3, JavaScript
- PWA: `manifest.json`, `sw.js` cache‑first strategy
- Works on modern browsers and installable as an app

## Development

- Main entry: `index.html`
- Styles: `style.css`
- Game logic: `game.js`
- PWA config: `manifest.json`, `sw.js`

Update `CACHE_NAME` in `sw.js` when deploying a new version.
