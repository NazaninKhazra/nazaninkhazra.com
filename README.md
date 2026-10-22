# nazaninkhazra.com

Personal academic site. Plain HTML and CSS on GitHub Pages; no build step. Edit a file, commit, push, and the site updates in about a minute.

## Pages
- `index.html` — home
- `teaching.html` — courses, course materials, resources for instructors and TAs
- `research.html` — working papers, pedagogy, book, student research symposia
- `news.html` — awards and certificates, press coverage, talks, service and volunteering
- `students.html` — "For Students": letters, guest lectures, RA positions, data catalogue
- `letters.html` — recommendation-letter policy
- `teaching-the-frontier.html` — guest-lecture programme for PhD students
- `data-catalogue.html` — Data for Economists catalogue (self-contained, data in the page's script)
- `econ-data-ta.html` — system prompt for the Econ Data TA
- `student-comments.html` — anonymous course-evaluation comments
- `resources.html` — redirect to `students.html` (old URL)

## Assets
- `assets/style.css` — all styling (shared by every page)
- `assets/photo.jpg` — portrait, 800×1000
- `assets/cv.pdf` — CV (linked from the nav and the home page)
- `assets/favicon.png`, `assets/apple-touch-icon.png` — site icon
- `assets/syllabi/`, `assets/materials/`, `assets/awards/` — PDFs linked from the Teaching and News pages

## Conventions
- The nav is copied by hand into every page: Home · Teaching · Research · For Students · News · CV. Change it everywhere at once.
- Every page has a `<meta name="description">` and Open Graph tags in `<head>`; add them to any new page.
- One narrow column, black on white, one burgundy accent (`#7a1f2b`). Source Serif headings, Inter body. No cards, buttons, or banners.
- Papers: title · "with Full Name" · status line · link row. No abstracts.

## Domain
`CNAME` holds `nazaninkhazra.com`. DNS is at Squarespace Domains (A records to GitHub Pages, `www` CNAME to the GitHub Pages host).
