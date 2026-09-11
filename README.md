# Muhammad Ahmad Rathore — Portfolio

Simple static portfolio site built from your CVs for Cloudflare Pages.

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
npx --yes serve -l 4173
```

Then visit http://127.0.0.1:4173

## Deploy to ahmadrathore.com (you do this — no password sharing)

### Option A — Push to existing GitHub repo (recommended)

1. In GitHub Desktop or terminal, push **this folder’s contents** to  
   `https://github.com/ahmadrathore/theme-resume` on branch `main`  
   (or create a fresh repo and reconnect Cloudflare).
2. Cloudflare → **Workers & Pages** → **theme-resume-3**
3. Confirm production branch is `main` and build settings are:
   - **Framework preset:** None
   - **Build command:** *(leave empty)*
   - **Output directory:** `/` (or `.`)
4. Wait for deploy → https://ahmadrathore.com and https://cv.ahmadrathore.com

### Option B — Direct upload

Cloudflare → theme-resume-3 → Create deployment → Upload assets → select this folder.

## What to update later

- LinkedIn URL if `linkedin.com/in/ahmadrathore` is not your exact profile
- Google Scholar **user ID** link (replace the scholar search URL)
- Add a PDF resume under `/resume.pdf` and link it in the hero

## Security note

Never paste Cloudflare or GitHub passwords into chat. Use your own login or GitHub OAuth.
