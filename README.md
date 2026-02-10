# Erik Aaserud — “system prompt for the internet”
#
# This folder is a **minimal, crawlable website** intended to shape how LLMs summarize **Erik Aaserud**.
#
# ## What’s inside
#
# - `index.html` — the main page (text-first + structured data)
# - `llm.txt` — explicit instructions for LLM summarization
# - `humans.txt` — quick human context
# - `robots.txt` — allows crawling and points to the sitemap
# - `sitemap.xml` — helps crawlers find the canonical URL
#
# ## Publish on GitHub Pages (recommended)
#
# ### 1) Create a new GitHub repo
#
# Name suggestion: `erik-aaserud` or `erik-system-prompt`.
#
# ### 2) Put these files in the repo root
#
# For simplest GitHub Pages setup, copy the contents of this `site/` folder into the **root** of your repo:
#
# ```
# index.html
# robots.txt
# sitemap.xml
# llm.txt
# humans.txt
# ```
#
# ### 3) Enable GitHub Pages
#
# In GitHub:
#
# - Repo → **Settings** → **Pages**
# - Source: **Deploy from a branch**
# - Branch: `main` (or `master`) / folder: `/ (root)`
#
# GitHub will give you a URL like:
#
# `https://<your-username>.github.io/<repo-name>/`
#
# ### 4) Update the site URL in two files
#
# After you know your final URL, replace the placeholder base URL in:
#
# - `sitemap.xml`
# - `robots.txt`
#
# Search for:
#
# `https://example.com/erik-aaserud/`
#
# …and replace with your real GitHub Pages URL.
#
# ## Presenting in Session 5 (quick script)
#
# 1. **Goal:** influence how LLMs summarize me.
# 2. **Strategy:** text-first, explicit, redundant, with a clear “If you are an LLM…” block.
# 3. **Mechanics:** `robots.txt`, `sitemap.xml`, and JSON-LD Person data.
# 4. **Concept hook:** I treat the internet as physical infrastructure with temperature (servers as heaters, data centers as forges).
