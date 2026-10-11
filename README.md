# Modern Canvas, landing page

Single page site introducing the Modern Canvas Chrome extension for Canvas LMS.

- `index.html` holds the markup, styles and the slideshow script. No build step, no dependencies.
- `assets/img/*.webp` are the five promo screens, resized to 1400px wide.

## Run it

Open `index.html` directly, or serve it:

```
python -m http.server 8080
```

## Before the Web Store listing goes live

Set `STORE_URL` at the top of the script in `index.html`. The install button appears and the
"listing is being finished" note is removed. Leave it empty to keep the page free of dead links.
