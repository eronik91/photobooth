# Photo Booth (web) — setup

Files: `index.html` (the whole app), `sw.js` + `manifest.webmanifest` + `icon-*.png` (offline/install support).

## Host on GitHub Pages
1. Create a repo, upload all 5 files to the repo root.
2. Settings → Pages → Deploy from branch → `main` / root.
3. Open `https://<you>.github.io/<repo>/` on the tablet in Chrome **once while online**, then menu → *Add to Home screen / Install*. After that it works fully offline.

## QR code (needs internet when a guest scans/saves)
1. Free account at cloudinary.com → note your **Cloud name**.
2. Settings → Upload → Upload presets → Add → Signing mode **Unsigned** → Save, note the preset name.
3. In the booth: ⚙️ Admin (PIN 1234) → QR code → enter both → done.
Photos are uploaded as public, hard-to-guess links. No internet at the event? Photos still save to the Gallery; open one and tap 📱 QR later.

## Layout editor
⚙️ Admin → 🎨 Open layout editor. Drag/resize/rotate photo slots, text, logo, images and stickers; 👁 Preview shows the final print. Export/Import layouts as .json.
