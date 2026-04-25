# Deployment Checklist — GEO Workbench Lab Before Page

## Local preview

- [ ] Open terminal in `geo-workbench-lab-pilot/`
- [ ] Run `python3 -m http.server 8088`
- [ ] Open `http://127.0.0.1:8088/`
- [ ] Confirm page loads
- [ ] Confirm CSS loads
- [ ] Confirm `before.html` loads
- [ ] Stop local server

## GitHub repo creation

- [ ] Create public repo named `geo-workbench-lab-pilot`
- [ ] Copy all files to repo root
- [ ] Commit before version
- [ ] Save before commit hash
- [ ] Push to main branch

## GitHub Pages setup

- [ ] Go to repo Settings
- [ ] Open Pages
- [ ] Select Deploy from branch
- [ ] Select `main` branch and `/root`
- [ ] Save
- [ ] Wait for deployment

## URL confirmation

- [ ] Open public URL
- [ ] Confirm status 200
- [ ] Confirm homepage loads
- [ ] Confirm `/before.html` loads
- [ ] Confirm public URL is copied into evidence folder

## Robots check

- [ ] Open `/robots.txt`
- [ ] Confirm `User-agent: *`
- [ ] Confirm `Allow: /`
- [ ] Update placeholder sitemap URL to real public URL

## Sitemap check

- [ ] Open `/sitemap.xml`
- [ ] Confirm homepage URL exists
- [ ] Confirm before.html URL exists
- [ ] Update placeholder URLs to real public URL

## Screenshot capture

- [ ] Capture before page screenshot
- [ ] Save to `05-screenshots-baseline/before-page.png`

## Before commit hash

- [ ] Save before commit hash
- [ ] Save deployment timestamp
- [ ] Do not edit page before baseline crawl and AI observation
