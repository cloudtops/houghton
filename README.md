# 10410 NE 58th Street — Property Site

Static one-page site, no build step required.

## Files
- `index.html` — the whole site (nav, hero, stats, room-by-room tour, gallery, contact)
- `favicon.ico`, `favicon.svg`, `apple-touch-icon.png` — site icons
- `og-image.png` — social share preview image (Facebook/iMessage/Twitter link previews)
- `images/` — all property photos used on the page

## Deploy to Vercel via GitHub
1. Create a new GitHub repo and push these files to it as-is (no `src/` folder needed — everything stays at the repo root).
2. Go to vercel.com → **Add New Project** → import that GitHub repo.
3. Framework preset: choose **Other** (it's plain HTML, no build command needed).
4. Deploy. Vercel will serve `index.html` at the root automatically.
5. Once live, add your custom domain (if any) under Project Settings → Domains.

## Updating content later
Everything — price, stats, MLS #, agent info, copy — lives directly in `index.html` as plain text/HTML, so it's easy to hand-edit. Swap photos by replacing files in `images/` (keep the same filenames, or update the `src=` paths in `index.html` if you rename them).
