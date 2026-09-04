# Dead Frequency

Find your Grateful Dead song in the static. A tiny mood-matching app — a single-page HTML prototype.

## Deploying on Railway

1. Push this repo to GitHub.
2. In Railway: **New Project → Deploy from GitHub repo** → select this repo.
3. Railway auto-detects Node and runs `npm start`, which serves `index.html` via `serve`.
4. Go to **Settings → Networking → Generate Domain** to get a public URL.
5. Every push to the main branch auto-redeploys.

## Notes

- This is a fully static, client-side app. No backend, database, or API.
- All choices (mood, ambiance, song picks) are computed client-side; nothing
  is saved or synced anywhere.
- No build step or dependencies to install locally — `package.json` only
  exists so Railway has a process to run.
