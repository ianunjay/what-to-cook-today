# What to Cook Today — PWA

## Files
- `index.html` — main app
- `sw.js` — service worker (offline support)
- `manifest.json` — PWA manifest
- `icon-192.png` / `icon-512.png` — app icons (generate below)

## Generate Icons (free, 2 minutes)
1. Go to https://realfavicongenerator.net or https://favicon.io
2. Upload any food/kitchen image or use a terracotta colored tile with a fork icon
3. Download and place `icon-192.png` and `icon-512.png` in this folder

## Deploy to GitHub Pages
1. Create a new GitHub repo (public)
2. Upload ALL files in this folder (index.html, sw.js, manifest.json, icon-192.png, icon-512.png)
3. Go to repo Settings → Pages → Source: main branch / root
4. Your app is live at https://yourusername.github.io/repo-name

## Install as App (Android)
1. Open the site in Chrome
2. Tap the "Install" banner that appears, OR
3. Tap Chrome menu (⋮) → "Add to Home screen"
4. Done — it's on your home screen like a native app, works offline

## Install as App (iPhone)
1. Open the site in Safari (must be Safari, not Chrome)
2. Tap the Share button (box with arrow)
3. Scroll down → "Add to Home Screen"
4. Done

## Notes
- All data is saved in localStorage on the device
- No login required, no server needed
- Works fully offline after first visit
