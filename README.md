# swimwarriorstester

Minimal static site for the Swim Warriors demo.

Build & run locally
 - Save static assets (images) into the `images/` folder.

Quick serve (no install):
```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Using npm script (uses `npx http-server`):
```bash
npm run start
# open http://localhost:8000
```

Deploy options
 - GitHub Pages: commit the files to `main` and enable Pages (root). Or run `gh pages deploy` with the `gh` CLI.
 - Netlify / Vercel: connect the repo or drag-and-drop the site folder to their dashboard.

Files added
 - `index.html` — site entry
 - `package.json` — convenience `start` script
 - `images/.gitkeep` — placeholder for image assets

Next steps
 - Replace the placeholder images in `images/` with real `.jpg` files (`hero.jpg`, `program1.jpg`, `program2.jpg`, `program3.jpg`).
 - Optionally add a small `404.html` and CI/CD for automatic deploys.