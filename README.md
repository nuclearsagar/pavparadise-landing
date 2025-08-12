# Pav Paradise – Independence Day Landing Page

A minimal, bilingual (EN/FI) static site for Pav Paradise.

## Structure
```
.
├─ index.html
├─ fi/
│  └─ index.html
└─ assets/
   ├─ logo-with-red-ring.png
   └─ archana-independence-day.jpg
```

## Local preview
Open `index.html` in your browser (no build needed).

## Deploy on Netlify (via Git)
1) Create a GitHub repo and push:
```bash
git init
git add .
git commit -m "Initial commit: Pav Paradise landing page"
git branch -M main
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin main
```
2) In Netlify: **Add new site → Import from Git** → select the repo.
   - Build command: *(leave empty)*
   - Publish directory: `/`

## Notes
- Update the Pre‑Order button URL in `index.html` (search for `example.com/preorder`).
- Replace `assets/archana-independence-day.jpg` and `assets/logo-with-red-ring.png` with your real images.
