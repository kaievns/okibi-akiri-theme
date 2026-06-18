# Okibi / Akari · 燠火 / 灯り

> Coal glow and ash — a color & syntax system built on a neutral charcoal base
> warmed by a single ember, with eight semantic hues. One discipline, two
> grounds: **Okibi** (dark) by night, **Akari** (light) by day.

The marketing/spec website for the theme, served as a static **GitHub Pages**
site.

## The site

[`index.html`](index.html) is fully self-contained — no build tooling,
framework, or JavaScript dependency at runtime. It includes:

- Okibi ⇄ Akari theme toggle (persisted in `localStorage`, respects the
  visitor's `prefers-color-scheme` on first visit)
- click-to-copy on every swatch and the token block (keyboard accessible)
- the ember-glow and blinking-caret accents
- responsive layout down to phone width

Assets: [`screenshots/`](screenshots/) (surface previews) and
[`favicon.svg`](favicon.svg). [`.nojekyll`](.nojekyll) tells Pages to serve
every path verbatim.

## Enable GitHub Pages

1. Push this repository to GitHub.
2. **Settings → Pages → Build and deployment → Source: _Deploy from a branch_.**
3. Branch: `main`, folder: `/ (root)`. Save.
4. The site goes live at `https://<user>.github.io/<repo>/` within a minute.

## Preview locally

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Repository layout

| Path | Purpose |
| --- | --- |
| `index.html` | the published static site |
| `favicon.svg`, `.nojekyll` | site assets / Pages config |
| `screenshots/` | surface preview images used on the page |

---

OKIBI / AKARI · v1.1 · coal glow & ash · niri rice
