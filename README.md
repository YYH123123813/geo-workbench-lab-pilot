# GEO Workbench Lab Pilot

This repository contains the intentionally weak `before` page for a self-owned real GEO pilot.

Project: GEO Workbench Lab  
Product: GEO Workbench  
Goal: test whether a local GEO Optimization Platform can take a weak public web page and improve crawlability, extractability, answerability, citation readiness, prompt coverage, and AI-search visibility signals.

## Why this page is intentionally weak

The before page is meant to be a realistic early-stage startup landing page, not a broken page. It should be crawlable and readable, but under-optimized for GEO.

It intentionally lacks:

- strong answer block
- detailed target audience section
- use case sections
- comparison table
- pricing / limitations section
- trust / evidence block
- expanded FAQ
- schema JSON-LD
- llms.txt
- detailed citation-friendly facts
- strong internal links
- off-page evidence references

This creates a clean baseline for the GEO platform to diagnose and improve.

## Files

- `index.html` — weak before page for deployment
- `before.html` — archived copy of the same weak before page
- `assets/style.css` — lightweight local CSS
- `robots.txt` — allows crawling
- `sitemap.xml` — placeholder GitHub Pages sitemap
- `pilot-materials/` — prompt pack, baseline test plan, ledger template, and deployment checklist

## Deploy to GitHub Pages

1. Create a new public GitHub repository named `geo-workbench-lab-pilot`.
2. Copy this folder's contents into the repository root.
3. Commit and push to the `main` branch.
4. Open GitHub repository settings.
5. Go to Pages.
6. Choose `Deploy from branch`.
7. Select branch `main` and folder `/root`.
8. Save.
9. Wait for GitHub Pages to publish.
10. Expected URL:

```text
https://YOUR_USERNAME.github.io/geo-workbench-lab-pilot/
```

After deployment, replace `YOUR_USERNAME` in `robots.txt` and `sitemap.xml` with your real GitHub username.

## Deploy to Vercel

1. Push this folder to a GitHub repository.
2. Open Vercel.
3. Import the repository.
4. Use the default static deployment settings.
5. Deploy.
6. Expected URL:

```text
https://geo-workbench-lab-pilot.vercel.app/
```

If you use Vercel, update `robots.txt` and `sitemap.xml` to the Vercel production URL.

## Local preview

From this folder, run:

```bash
python3 -m http.server 8088
```

Open:

```text
http://127.0.0.1:8088/
```

Stop the server with `Ctrl+C`.

## Evidence to collect before optimization

Before changing the page, collect:

- public target URL
- deployment timestamp
- before commit hash
- before page screenshot
- crawl result
- extraction result
- audit result
- prompt pack used
- baseline answer ledger
- raw AI platform answers
- baseline AI platform screenshots where possible

## Do not add these yet

Do not add these before the baseline test:

- `llms.txt`
- schema JSON-LD
- expanded FAQ
- comparison table
- detailed trust block
- pricing / limitations block
- citation-ready evidence section
- optimized answer block

Those should be generated or recommended by the GEO platform after diagnosis.

## What the GEO platform should discover

The platform should detect:

- unclear category definition
- weak answerability
- thin FAQ
- no comparison table
- no trust block
- no pricing / limitations
- no schema
- no llms.txt
- weak citation readiness
- weak prompt coverage
- missing target audience detail
- weak use-case coverage

## Current baseline status

This package does not claim any real AI platform result.
No real crawl, AI answer, citation, or screenshot evidence is included yet.
