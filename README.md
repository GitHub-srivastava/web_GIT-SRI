# Personal Academic Website

This is a multi-page static website for GitHub Pages.

## Pages

- `index.html` - homepage and research summary
- `research.html` - dedicated research objectives with image preview and animation controls
- `experience.html` - research roles, education, teaching, and honors
- `publications.html` - selected publications
- `tools.html` - models, apps, and technical skills
- `contact.html` - contact links

## Assets

- `assets/css/styles.css` - complete styling and animations
- `assets/js/main.js` - mobile menu, scroll reveal animation, and objective media settings
- `assets/images/` - default SVG images for research objectives

## Important note about image uploads

The image upload controls on `research.html` are browser-side previews. They work on GitHub Pages without a backend, but they do not permanently upload images to the repository.

To permanently change an objective image:

1. Add your image to `assets/images/`.
2. Open `research.html`.
3. Replace the relevant `<img src="assets/images/...">` path.
4. Commit and push the changes to GitHub.

## Deploying on GitHub Pages

Use the `main` branch and the repository root as the GitHub Pages source.
