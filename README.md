# Moonscreen



## What it is

A single, self-contained `index.html` — no build step, no dependencies (fonts load from Google Fonts). Just open it in a browser.

Sections: hero with an animated moon, the "threat," how it works, stats, testimonials, pricing, and an FAQ.

## Run locally

Open the file directly:

```sh
open index.html
```

Or serve it:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy on GitHub Pages

Push to GitHub, then in **Settings → Pages**, set the source to the `main` branch (root). Your site will be live at `https://<username>.github.io/moonscreen/`.
