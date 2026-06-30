# Minimal Academic Website for Chris J. Ploetz

This version is intentionally modeled after a clean academic GitHub Pages site: simple header, horizontal navigation, concise pages, and minimal styling.

## Important files

- `index.html` — About / homepage
- `research.html`
- `teaching.html`
- `fieldwork.html`
- `publications.html`
- `contact.html`
- `assets/style.css`
- `assets/Chris_Ploetz_CV.docx`

## To update the homepage image

1. Add an image named `homepage.jpg` to the `assets` folder.
2. In `index.html`, replace the current `<div class="hero-image">...</div>` block with:

```html
<div class="hero-image has-image">
  <img src="assets/homepage.jpg" alt="Chris Ploetz fieldwork image">
</div>
```

## Deployment

Upload these files to the root of your `GeoPloetz.github.io` repository.