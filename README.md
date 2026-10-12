# DS Sprint

Landing page for DS Sprint: an AI-enabled design system, set up in a two-week fixed-price sprint.

The whole site is one static file, `index.html` (styles, scripts and client logos are inline), so it needs no build step.

## Preview locally

```bash
ruby -run -e httpd . -p 8000
```

Then open http://localhost:8000.

## Deploy

Copy `index.html` into `dist/` and drag that folder onto Netlify, or connect this repo to Netlify. The booking form submits to Netlify Forms once the site is live on Netlify.

## Logos

`tools/logos.py` turns the files in `assets/logos` into the inline masks used in the "Trusted by" strip (needs Python with Pillow).
