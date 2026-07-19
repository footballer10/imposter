# Impostor — pass-and-play party game (PWA)

One phone. 3–12 players. Somebody here doesn't know the word.
59 categories · 3,382 words · fully offline once installed.

## Files
- `index.html` — the entire game (no dependencies, works offline)
- `manifest.json` — PWA manifest (standalone fullscreen)
- `sw.js` — service worker (offline caching)
- `icons/` — put your app icons here (see icons/README.txt for exact names/sizes)

## Deploy on GitHub Pages
1. Create a **public** repository (e.g. `impostor`).
2. Upload everything in this folder, keeping the `icons/` folder structure.
3. Repo **Settings → Pages → Source: Deploy from a branch → main → / (root) → Save**.
4. Wait ~1–2 minutes. Your game is at `https://YOUR-USERNAME.github.io/impostor/`.

## Install on iPhone
Open the URL in **Safari** → Share button → **Add to Home Screen** → **Add**.
Launch from the icon: fullscreen, no Safari UI, works in Airplane Mode.

## Updating later
Edit files, commit, then bump the cache name in `sw.js`
(`impostor-v1` → `impostor-v2`) so installed phones fetch the new version.
