# Kiran M. Jayasurya — Academic Website

Responsive, single-page academic website built with plain HTML and CSS for GitHub Pages.

## Features
- Light/dark mode toggle, remembers the visitor's choice
- Uses the native Apple system font stack on Apple devices (`-apple-system`, `BlinkMacSystemFont`); falls back to system UI fonts elsewhere
- Responsive mobile navigation
- Research, publications, observing, biography, CV, and contact sections
- Search, authorship, and year filters for the publication list
- No build process, Ruby, or Jekyll required

## Publish
1. Create a public repository named `YOUR-USERNAME.github.io`.
2. Upload `index.html`, `styles.css`, and the `assets` folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Choose **Deploy from a branch**, branch `main`, folder `/(root)`, then save.
5. Wait for the site to publish at `https://YOUR-USERNAME.github.io/`.

## Personalize before publishing
In `index.html`, search for `YOUR.EMAIL@INSTITUTION.EDU`, `Add your institution`, `Replace with`, `Publication placeholder`, and `YEAR–YEAR`. Replace all placeholders with accurate details or remove them.

- Update ORCID, Google Scholar, NASA ADS, GitHub, and institutional profile links.
- Replace the example publication card with real verified bibliographic metadata. Duplicate the `<article class="publication-item" ...>` block for each paper. Set `data-year` to the paper's year and `data-authorship` to `first` or `co`.
- Add your CV as `assets/pdf/CV.pdf`.
- Remove the Observing section if you do not want it.
- Check the descriptions carefully before publishing; starter research topics are not a substitute for a verified biography.

## Apple fonts
The stylesheet uses the operating system's built-in San Francisco/system font stack. On macOS and iOS it should use the native Apple UI font; on Windows/Linux it uses suitable local system fallbacks. Apple proprietary font files are not bundled.

## Theme
The button in the navigation switches between light and dark themes. The choice is stored in local storage. On a first visit, the page follows the visitor's operating-system appearance preference.
