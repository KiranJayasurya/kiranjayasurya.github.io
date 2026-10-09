# Kiran M. Jayasurya — Academic Website

A responsive single-page academic website built with plain HTML and CSS for GitHub Pages.

## Files
- `index.html` — all page content and navigation
- `styles.css` — colors, typography, layout, and responsive design
- `assets/pdf/CV.pdf` — place your CV PDF here
- `assets/img/` — optional images if you later add a profile photo

## Publish with GitHub Pages
1. Create a public GitHub repository named `YOUR-USERNAME.github.io`.
2. Upload `index.html`, `styles.css`, and the `assets` folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. Wait a few minutes and open `https://YOUR-USERNAME.github.io/`.

## Personalize before publishing
Search `index.html` for:
- `YOUR.EMAIL@INSTITUTION.EDU` and `mailto:YOUR.EMAIL@INSTITUTION.EDU`
- the ORCID, Google Scholar, and GitHub links
- `Replace with your publication title`
- `Your name and co-authors`
- the sample journal details and project descriptions

The sample publication is intentionally a placeholder. Replace it with a verified publication or remove the sample block. Update research descriptions so they accurately represent your work.

## Add your CV
Upload your CV as `assets/pdf/CV.pdf`. The CV link on the page points to that path. If you use another filename, update the link in `index.html`.

## Edit the design
Change CSS custom properties near the top of `styles.css`:
- `--paper`: page background
- `--ink`: primary text
- `--accent`: rust accent
- `--serif` and `--sans`: typefaces

The page uses Google Fonts when online and falls back to system fonts if those fonts are unavailable.
