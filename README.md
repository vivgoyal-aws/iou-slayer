# ☠️ IOU Slayer

**Slay those IOUs among friends.**

A lightweight, offline-capable expense splitter for group trips. Add expenses, mark who paid and who participated, and instantly see who owes whom — no sign-up, no server, no tracking.

## Features

- **Unlimited friends & expenses** — no caps, no tiers
- **Instant settlement plan** — see exactly who pays whom to settle up
- **Works offline** — installable as a PWA on your phone
- **Data stays on your device** — saved to localStorage, never leaves your browser
- **Zero dependencies at runtime** — single HTML file + React from CDN
- **Mobile-first** — responsive design for phone, tablet, and desktop

## Usage

1. Open `index.html` in a browser, or visit the hosted version
2. **Setup** — add your group's names
3. **Expenses** — log each expense: who paid, how much, who was in on it
4. **Summary** — see the settlement plan (who owes whom)

Save/load your quest as a JSON file to share or back up.

## Install as an App

Deploy to any static host (GitHub Pages, Netlify, Vercel), then:

- **iPhone**: Safari → Share → "Add to Home Screen"
- **Android**: Chrome → ⋮ → "Install app"

The app works offline after first load.

## Local Development

No build step. Just open `index.html` in a browser.

```
iou-slayer/
├── index.html        # The app (React SPA)
├── manifest.json     # PWA manifest
├── sw.js             # Service worker for offline support
├── icon-192.png      # App icon
├── icon-512.png      # App icon (high-res)
└── icon.svg          # App icon (vector)
```

## License

MIT
