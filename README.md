# GOON ETERNAL

A single-file browser game. Everything (code, art, audio) lives in `index.html`; there is no build step.

## Run locally
Open `index.html` in a browser, or run `npx serve .`

## Deploy to GitHub Pages
1. Push this folder to a new GitHub repo.
2. Repo Settings > Pages > Source: "Deploy from a branch" > `main` / `(root)`.
3. Your game will be at `https://<user>.github.io/<repo>/`.

## Deploy to Vercel
1. Push to GitHub, then import the repo at vercel.com/new.
2. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
3. Click Deploy.

Or from the terminal: `npx vercel --prod`
