# Trust Fertility — Landing Page

Single-page marketing site for Trust Fertility, a fertility clinic. Built as one self-contained `index.html` file (HTML + CSS + JS inline, logo embedded as base64) so it can be hosted on any static host with zero build step.

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```powershell
# Python
python -m http.server 8000

# Node
npx serve .
```

Then visit http://localhost:8000.

## Deploy

### GitHub Pages
1. Push this repo to GitHub.
2. **Settings → Pages → Source:** `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. Site will be available at `https://<user>.github.io/<repo>/`.

### Other static hosts
The folder is drop-in compatible with Netlify, Vercel, Cloudflare Pages, S3, etc. — point them at the repo root, no build command needed.

## Files

- `index.html` — the landing page (logo embedded inline)
- `trust-logo.png` — standalone logo asset
