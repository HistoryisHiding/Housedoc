# HouseDoc – Walkthrough Journal (PWA)

Upload these files to the **root** of a public GitHub repository and enable **GitHub Pages** (Settings → Pages → Deploy from branch: `main` / root).

Then open: `https://<your-username>.github.io/<repo-name>/` on iPhone → **Share → Add to Home Screen**.

Included:
- `index.html` — the app UI (photos, video, narration, GPS, notes; exports a single-file HTML report)
- `manifest.webmanifest` — install metadata
- `service-worker.js` — offline cache
- `icons/` — app icons

Notes:
- Long videos will make exported reports large; prefer shorter clips.
- All data remains in the browser until you export/share it.
