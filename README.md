# ReMeDic (remedic_v38) - GitHub Pages package

Split layout: `index.html` (about 12 MB) + `packs/*.langpack.json` (largest about 10 MB). Every file is under 25 MB, so it uploads from the GitHub web UI too.

## Steps
1. Create a new repository on GitHub, e.g. `remedic`.
2. Upload the CONTENT of this folder to the repo root (index.html, packs/, config.js, sw.js, manifest.webmanifest, icons, .nojekyll and the hidden `.github` folder). With git: `git add . && git commit -m "remedic" && git push`.
3. Settings > Pages > Source = "GitHub Actions" (the included workflow deploys on every push to `main`). Alternatively choose "Deploy from a branch" > main > / (root).
4. Open `https://<user>.github.io/<repo>/`.

On iPhone: open the link in Safari > Share > Add to Home Screen.
