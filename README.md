# Gerardo M. Casanola-Martin — Academic Website

A responsive static academic website prepared for GitHub Pages. Its information was curated from the supplied CV, with a layout inspired by academic profile sites that use a profile sidebar and section-based navigation.

## Preview locally

Open `index.html` directly in a browser, or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Replace the profile image

1. Add a square portrait at `assets/img/profile.jpg`.
2. In each HTML file, replace:

```html
src="assets/img/profile-placeholder.svg"
```

with:

```html
src="assets/img/profile.jpg"
```

A 1000 × 1000 pixel JPG or WebP works well.

## Publish with GitHub Pages

1. Create a GitHub repository named `YOUR-USERNAME.github.io`.
2. Upload the contents of this folder to the repository root.
3. Commit and push to the `main` branch.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**, then choose `main` and `/ (root)`.

The site will be available at `https://YOUR-USERNAME.github.io/`.

## Recommended final edits

- Add a professional portrait.
- Add your Google Scholar URL if desired.
- Check the 2026 publication citations as final volume/page details become available.
- Convert the CV to PDF and change the CV link if PDF is preferred.
- Add DOI or publisher links to selected publications.

## Files

- `index.html` — home/about page
- `research.html` — research themes and funded projects
- `publications.html` — searchable list of 77 CV publications
- `teaching.html` — teaching experience
- `talks.html` — talks, awards, and professional service
- `cv.html` — concise online CV
- `assets/css/styles.css` — all design settings
- `assets/js/publications-data.js` — publication data generated from the CV
- `assets/files/` — downloadable CV
