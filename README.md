# Homepage

A minimal static site built with [Eleventy](https://www.11ty.dev/).

## Setup

```bash
npm install
```

## Develop

```bash
npm run dev
```

Opens at `http://localhost:8080` with live reload.

## Build

```bash
npm run build
```

Output goes to `dist/`. Deploy that folder to any static host (Netlify, Vercel, GitHub Pages, etc.).

## Structure

- `src/` — source files
  - `_includes/` — layouts (Nunjucks)
  - `_data/` — global data (e.g. `site.json`)
  - `*.njk`, `*.md` — pages
  - `css/` — styles (copied as-is)
  - `assets/` — images, etc. (copied as-is)

Edit `src/index.njk` and `src/_data/site.json` to customize your name, links, and copy.
