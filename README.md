# Cartessa Real Estate Company: website concept

A redesign concept for [cartessarep.com](https://cartessarep.com) and the
[Westwood Apartments](https://www.westwood248.com) leasing site, prepared for
Bill and Billy Chalmers by Jason Kemp.

**Live preview:** https://jasonkemp21.github.io/cartessa-site/

## What's in it

- Home, About, Development Portfolio, Articles & Testimonials, Contact
- A sub-site for each of the 26 projects. Each family has its own layout and
  type, and each property has its own street map, diagram and facts
- Leasing-style sites for the four properties that have their own websites
  today: Westwood, The 819, Miami Garden and North Greenfield Office Park,
  using their real logos, colors, photos and floor plans
- A draggable before/after of North Greenfield Office Park, from the completion package

## Where the content comes from

Project history, costs and dates are Cartessa's own, from its current websites
and the North Greenfield completion package. Addresses, opening dates,
present-day occupants and other public-record details were researched for this
concept and are listed with links in a Sources line at the bottom of each
sub-site. Street maps are drawn from OpenStreetMap data (© OpenStreetMap
contributors) and live in `maps/`.

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
