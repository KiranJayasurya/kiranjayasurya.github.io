# Kiran M. Jayasurya — academic website

A static academic website for GitHub Pages. It uses plain HTML and CSS, with no build tools or external font downloads.

## Design choices

- One Apple system-font stack across the entire site; hierarchy comes from size and font weight.
- No italic styling or differently coloured final words in headings.
- Pure white light theme by default, with an optional dark-mode toggle.
- Responsive layout, mobile navigation, publication search and year/type filters.
- Research, Publications, About, and Contact sections; no Observing section.
- `publications.bib` contains BibTeX entries based on the CV details supplied. Please verify author metadata before formal reuse.

## Before publishing

1. Add your CV PDF as `assets/pdf/CV.pdf` so the download link works.
2. Check publication metadata and author lists, especially the fourth 2025 XSPECT entry, which was transcribed from the CV as supplied.
3. Review the biography, role, degree dates, and contact details for accuracy.

## Publish with GitHub Pages

1. Create a public repository named `YOUR-USERNAME.github.io` (replace with your GitHub username).
2. Upload the contents of this folder to the repository root: `index.html`, `styles.css`, `publications.bib`, `README.md`, and `assets/`.
3. In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
4. After GitHub Pages finishes deploying, visit `https://YOUR-USERNAME.github.io/`.

The site defaults to a clean white background even if the operating system is in dark mode. The toggle lets visitors switch themes; their choice is remembered in the browser. The font stack uses system fonts including Apple's San Francisco where available; it does not redistribute Apple's proprietary font files.
