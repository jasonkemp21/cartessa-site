# Cartessa Real Estate Company — website concept

A redesign concept for [cartessarep.com](https://cartessarep.com) and the
[Westwood Apartments](https://www.westwood248.com) leasing site, prepared for
Bill and Billy Chalmers by Jason Kemp.

**Live preview:** https://jasonkemp21.github.io/cartessa-site/

## What's in it

- Home, About, Development Portfolio (all 26 projects, each with its own page),
  Articles & Testimonials, Contact
- Westwood Apartments as its own section with its own branding
- A draggable before/after of North Greenfield Office Park, from the completion package

Everything on the site (copy, figures, photos, quotes) comes from Cartessa's
current websites and the North Greenfield completion package.

## How it's built

One `index.html` with no build step or framework. Pages are routed by hash
(`#portfolio-office`, `#property-the-819`, `#westwood`), so it hosts anywhere
static files do. Images live in `img/`; the older portfolio photos are the
300px originals from the current site and are the first thing to replace with
higher-resolution shots.

## Running locally

Open `index.html` in a browser, or:

```
python3 -m http.server 8000
```

and visit http://localhost:8000.
