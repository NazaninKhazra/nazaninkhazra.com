# nazaninkhazra.com

Plain HTML site, hosted on GitHub Pages. No build step.

## Files
- `index.html`, `research.html`, `teaching.html`, `students.html`, `letters.html` — the pages
- `assets/style.css` — all styling
- `assets/photo.jpg` — ADD THIS (your portrait; ~800px wide is plenty). Then in `index.html` replace
  `<div class="photo">Add assets/photo.jpg</div>` with `<img src="assets/photo.jpg" alt="Nazanin Khazra">`
- `assets/cv.pdf` — ADD THIS (the CV link in the nav points here)
- `CNAME` — tells GitHub Pages your domain

## Publish (one time)
1. Create a new public repo on GitHub named `nazaninkhazra.com` (any name works).
2. Upload everything in this folder (drag-and-drop on GitHub works, or `git push`).
3. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
4. Settings → Pages → Custom domain: `nazaninkhazra.com` → Save. Tick "Enforce HTTPS" once it appears.

## Point your Google domain at GitHub
In Google Domains / Squarespace Domains → DNS → custom records, add:

| Type  | Host | Data |
|-------|------|------|
| A     | @    | 185.199.108.153 |
| A     | @    | 185.199.109.153 |
| A     | @    | 185.199.110.153 |
| A     | @    | 185.199.111.153 |
| CNAME | www  | YOUR-GITHUB-USERNAME.github.io |

Delete the old records that pointed to Google Sites. DNS takes up to a few hours.

## Editing
Edit the `.html` file, commit, done. The site updates in about a minute.
Nav is copied at the top of each page — if you add a page, add the link in all five files.
