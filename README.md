# My Photo Site (simple)

Hey — I'm 15 and this is a tiny photo website I made. It's just HTML and CSS, super simple so you can learn and change stuff fast.

What it is:

- A gallery page that shows pictures.
- No fancy tools or installs — just files you can edit.

How to open it:

Open `index.html` in your browser, or run one command to serve it locally:

```bash
python3 -m http.server 8000
# then go to http://localhost:8000
```

Easy code you can try:

- Add a photo in `index.html`:

```html
<figure class="photo">
  <img src="images/my-photo.jpg" alt="My photo" />
  <figcaption>My caption</figcaption>
</figure>
```

- Make images fit (put this in `styles.css`):

```css
.photo img {
  max-width: 100%;
  height: auto;
  display: block;
}
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 12px;
}
```

How to explain this (practice script):

- Intro (1 sentence): "This is a simple photo website I built with HTML and CSS."
- Files (1 sentence): "`index.html` has the page structure, `styles.css` has the design, and `images/` has the pictures."
- How it works (2 sentences): "Images are shown using `<img>` inside `<figure>` so we can add captions. CSS makes the pictures resize and put them in a grid so it looks nice on phones."
- How you run it (1 sentence): "Open `index.html` or run `python3 -m http.server 8000` and go to `http://localhost:8000`."
- One thing you changed (1 sentence): "I can add photos by copying files into `images/` and adding the HTML snippet."

Want me to make the explanation even shorter for a 30-second talk? Or add screenshots to the README?
