# Toolsey — Seed Round Pitch Deck

Live, browser-based pitch deck. Self-contained single HTML file — all CSS, JavaScript, and images are inlined.

## Deploy to Vercel via GitHub

### 1. Create a new GitHub repo

- Go to <https://github.com/new>
- Name it something like `toolsey-pitch` (or whatever you like)
- Make it **private** (recommended for a pitch deck)
- Don't initialize with a README — you're about to upload one
- Click **Create repository**

### 2. Upload the files

On the empty repo page, click **uploading an existing file**, then drag in:

- `index.html` (the deck — ~1.6 MB)
- `vercel.json` (cache + security headers)
- `README.md` (this file)

Commit them straight to `main`.

### 3. Connect to Vercel

- Go to <https://vercel.com/new>
- Click **Import** next to your new GitHub repo
- Leave all defaults — Vercel auto-detects this as a static site
- Click **Deploy**

In about 30 seconds you'll get a live URL like `toolsey-pitch.vercel.app`.

### 4. (Optional) Add a custom domain

In the Vercel dashboard → Project → Settings → Domains, you can attach any domain you own (e.g. `deck.toolsey.com` or `pitch.toolsey.com`). Vercel will give you the DNS records to add at your registrar.

## Updating the deck

Edit `index.html` locally (or directly in GitHub's web editor) and push the change. Vercel will redeploy automatically — usually within 30 seconds.

## Controls (in browser)

- **→ / Space / PgDn** — next slide
- **← / PgUp** — previous slide
- **F** — fullscreen
- **Cmd/Ctrl+P** — print / save as PDF

---

© Toolsey, Inc. — Confidential.
