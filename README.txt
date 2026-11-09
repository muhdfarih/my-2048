MY 2048 — QUICK START

Files:
- index.html: the complete playable game
- manifest.webmanifest and sw.js: PWA installation/offline support

Quick test:
1. Open index.html in a modern browser. Gameplay and local saving work.
2. For install/offline PWA support, host the folder on an HTTPS static host (for example GitHub Pages or Netlify).
3. Open the hosted URL in Chrome on Android and choose Install app / Add to Home screen.

Features:
- Classic, One Undo, Two Undos, Custom Board modes
- Custom 4x4 board with power-of-two validation
- Custom starting score
- Presets saved locally
- Undo restores board, score and move count
- Local autosave, resume, JSON export/import
- Score, best tile, move count and run history
- Keyboard and swipe controls

Note: browser local storage is local to that browser/device. Export a JSON backup before clearing browser data.
