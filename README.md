# Brian's Build Log — static site bundle

Drop everything in this folder into the root of your GitHub repo (or any static host), then enable GitHub Pages:

1. Push these files to your repo (e.g. `main` branch, root folder — or a `/docs` folder, your call).
2. On GitHub: **Settings → Pages → Source** → pick the branch/folder you used → Save.
3. GitHub gives you a URL like `https://<username>.github.io/<repo>/` within a minute or two.

## Files
- `index.html` — home page
- `video-space.html` — Video Parameter Space project page
- `content-space-3d.html` — interactive 3D prototype (React + Three.js via CDN — needs a real host to run, which is exactly what this fixes)
- `video-parameter-space-paper.html` — full research paper, with `graph-1.jpg` / `graph-2.jpg`
- `style.css` — shared site styles

## Not included
`truss-bridge.html` wasn't touched this round and still lives only in your Drive `[01]Git` folder — grab it from there and drop it in alongside these before you push, so the nav links between all pages resolve.
