# ORDYNA — Business, rethought.

Static website (HTML, CSS, JavaScript). No build step. Works on GitHub Pages as-is.

## Publish on GitHub Pages
1. On GitHub, create a new repository (for example `ordyna-site`, or `YOUR-USERNAME.github.io` for a root address).
2. Upload **all files in this folder** (Add file → Upload files). `index.html` must be at the repository root.
3. Go to **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After a minute or two the site appears at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

Or with Git:
```
git init && git add . && git commit -m "ORDYNA website v1"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/REPO-NAME.git
git push -u origin main
```

## Before sharing publicly — replace placeholders
- `sitemap.xml` and `robots.txt`: replace `YOUR-USERNAME` / `YOUR-REPO` with your real address.
- `index.html`: set `og:image` to the full address of `og-image.png` (e.g. `https://YOUR-USERNAME.github.io/REPO-NAME/og-image.png`) so link previews work.
- Contact email is `info.ordyna@gmail.com`. Search `index.html` to change it.

## Known limits of this version
- Pages use `#` navigation (single-page site), so search engines will index mainly the home page. A multi-page build (e.g. Next.js) is recommended for SEO.
- The contact form opens the visitor's email app (`mailto:`). It does not store or send data by itself. Connect a form service before relying on it.
- Privacy Policy and Terms of Use are **drafts**. Have them reviewed professionally (including Saudi PDPL) before collecting real inquiries.
- Example scenarios are conceptual, not client projects. Do not present them as real work.
- The hero head image and reference-derived artwork: confirm you hold usage rights before commercial use.
