# Photography Website

A minimal photography portfolio website with a simple, static HTML/CSS structure. Designed to be easy to read, edit, and deploy — perfect for sharing photos or learning how static sites work.

## Features

- Clean, responsive gallery layout
- Easy-to-edit HTML and CSS (no build tools required)
- Works locally by opening `index.html` or serving with a tiny web server

## Quick Start

1. Open the site in your browser:

```bash
open index.html
```

2. Or serve locally with Python (recommended for correct image loading):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Simple Code Examples

- Basic gallery item (add inside your gallery container in `index.html`):

```html
<figure class="photo">
  <img src="images/photo1.jpg" alt="A descriptive caption" />
  <figcaption>A short caption</figcaption>
</figure>
```

- Minimal CSS to keep images responsive (add to `styles.css`):

```css
.photo img {
  max-width: 100%;
  height: auto;
  display: block;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 16px;
}
```

## Customize

- Replace images in the `images/` folder and update `index.html` markup.
- Tweak colors and spacing in `styles.css`.

## License

This project is free to use and modify.

---
