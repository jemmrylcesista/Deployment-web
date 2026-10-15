# Snake

A simple Snake game for the browser (plain HTML, CSS and JavaScript, no build step).

## Play
Arrow keys or WASD to move, Space to pause. On phones, swipe on the board or use the on-screen buttons.

## Run locally
Double-click `index.html`, or run `npx serve` in this folder.

## Upload to GitHub
```bash
git init
git add .
git commit -m "Initial Snake game"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/snake-game.git
git push -u origin main
```
(Create an empty repo named `snake-game` on github.com first. Don't add a README there.)

## Deploy on Vercel
1. Sign in at https://vercel.com with GitHub.
2. Click **Add New → Project** and import the `snake-game` repo.
3. Leave Framework Preset as **Other**. Leave Build Command and Output Directory empty.
4. Click **Deploy**.

Every `git push` to `main` redeploys the site.
