# Kiran M. Jayasurya — academic website

A static academic website for GitHub Pages. It uses plain HTML and CSS, with no build tools or external font downloads.

## Design and content

- One Apple/system sans-serif font family throughout; hierarchy comes from size and weight.
- Pure-white light theme by default, with an optional dark-mode toggle.
- Responsive layout, mobile navigation, and publication search/type/year filters.
- Publications are grouped by year (newest first), with numbered entries within each year. The list was generated from `publications.bib` supplied by Kiran.
- Sections: Research, Publications, About, and Contact. There is no Observing section.
- Downloadable CV at `assets/pdf/CV.pdf`.

## Before publishing

1. Check the generated publication display against the source BibTeX, especially any author fields that are incomplete or inconsistent in `publications.bib`.
2. Review the biography, role, degree dates, and contact details for accuracy.
3. Replace `assets/pdf/CV.pdf` if you want to use a newer CV.

## Publish with GitHub Pages

1. Create a public repository named `YOUR-USERNAME.github.io` (replace with your GitHub username).
2. Upload the contents of this folder to the repository root: `index.html`, `styles.css`, `publications.bib`, `README.md`, and `assets/`.
3. In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
4. After GitHub Pages finishes deploying, visit `https://YOUR-USERNAME.github.io/`.

The website defaults to pure white in light mode. The theme toggle remembers the visitor's choice. The font stack uses system fonts including Apple's San Francisco where available; it does not redistribute proprietary Apple font files.
