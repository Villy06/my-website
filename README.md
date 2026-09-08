# Havoc City Roleplay

A Next.js landing page for the Havoc City Roleplay FiveM roleplay server.

## Run locally

```bash
npm install
npm run dev
```

Then open http://localhost:3000

## What to edit before launch

- `app/page.js`
  - `DISCORD_URL` at the top — swap in your real Discord invite.
  - The four `EDIT` values in the "Live Snapshot" panel — real stats look
    better than placeholders.
  - Copy in the Systems, Departments, and CTA sections — adjust to match
    what your server actually offers.
- `app/layout.js` — page title and meta description.

## Deploy to Vercel

**Option A — Vercel dashboard**
1. Push this folder to a GitHub repo.
2. Go to vercel.com → New Project → import the repo.
3. Framework preset auto-detects as Next.js. Click Deploy.

**Option B — Vercel CLI**
```bash
npm install -g vercel
vercel
```
Follow the prompts; it deploys straight from this folder.
