# Lujain Aljabri – Data Analyst Portfolio

Static bilingual (Arabic / English) portfolio. No build step and no server needed.

## Files
- `index.html` – the whole website (must stay at the repository root)
- `404.html` – custom "page not found" page
- `robots.txt`
- `assets/` – everything the site loads: `resume.pdf` (the CV), project page images (`*.webp`),
  original project PDFs (`*.pdf`), favicon (`favicon.svg`, `apple-touch-icon.png`)

## Updating content
- New CV: replace `assets/resume.pdf` with a file of the same name.
- Text, experience and project findings: edit the `CONFIG`, `PROJECTS` and `JOBS` blocks near the top of the `<script>` in `index.html`.
- Gallery images: replace the `.webp` files in `assets/` using the same names.
