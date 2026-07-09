# album-keeper

A tiny offline‑first web app that lets you store the albums you’ve listened to,
rate them and keep a cover image. All data lives in the browser’s
`localStorage`, so it works without any server.

## Demo

Visit the live page at: https://YOUR_USERNAME.github.io/album-keeper/

## How to run locally

1. Clone the repo or just open `index.html` in a browser.
2. Add albums → they are saved in `localStorage`.
3. Close the tab → reopen → data is still there.

## Deploy to GitHub Pages

1. **Create a new repo** called `album-keeper` (or any name you like).  
2. Copy the `index.html` file into the root of the repo.  
3. Commit & push:

```bash
git init
git add index.html
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/album-keeper.git
git push -u origin main
