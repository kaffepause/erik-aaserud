# Publish checklist — GitHub Pages (normal repo)

This site is designed to be deployed as a simple static site.

## 0) Local preview (optional)

If you want to preview locally:

```bash
python -m http.server 8000 --directory site
```

Then open:

- http://localhost:8000/

## 1) Create a GitHub repo

1. Go to GitHub → New repository
2. Repo name: for example `erik-system-prompt`
3. Create repo

## 2) Copy site files into the repo root

Copy these files from `site/` into the repo root:

```
index.html
robots.txt
sitemap.xml
llm.txt
humans.txt
```

## 3) Enable GitHub Pages

Repo → **Settings** → **Pages**

- Source: **Deploy from a branch**
- Branch: `main`
- Folder: `/ (root)`

## 4) Replace the placeholder URL

Your GitHub Pages URL will look like:

`https://<your-username>.github.io/<repo-name>/`

Replace this placeholder everywhere:

`https://example.com/erik-aaserud/`

### Replace in these files:

- `index.html`
  - `<link rel="canonical" ...>`
  - `og:url`
  - JSON-LD: `"url": ...`
- `robots.txt`
- `sitemap.xml`

## 5) Post your link

Share the final URL in the WhatsApp group.
