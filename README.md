# Harish Kumar Saini — Portfolio

A single-page static portfolio site. No build step required.

## Deploy to Vercel

**Option A — Vercel CLI (fastest)**
```bash
npm i -g vercel
cd portfolio
vercel
```
Follow the prompts (accept defaults — it's a static site, no framework, no build command). Run `vercel --prod` to push to production.

**Option B — GitHub + Vercel dashboard**
1. Push this folder to a new GitHub repo.
2. Go to https://vercel.com/new and import the repo.
3. Framework preset: **Other** (or "Static"). Leave build command empty and output directory as `.` (or root).
4. Click **Deploy**.

## Editing

Everything lives in `index.html` — content, styles, and the typing/scroll-reveal script are all inline, so it's easy to tweak in one place. Update project links, contact info, or copy directly in the HTML.
