# Peachtree Solutions — Concept Redesign

A self-contained, single-file concept mockup built for Peachtree Solutions
(an independent Medicare, Life & Wealth insurance agency founded by Lori
Ahlbrandt), created as a design example by FlowReign Solutions.

## Files

- `index.html` — the entire page (markup, CSS, and images) in one file.
  Fonts (Fraunces, Playfair Display, Public Sans, Archivo) load from Google
  Fonts; the logo and watermark art are embedded as base64 data URIs, so the
  file has no external asset dependencies beyond the font CDN.

## Editing

Open `index.html` in any editor — all styles are in the `<style>` block in
`<head>`, all markup follows in `<body>`. No build step required.

## Deploying

Because it's a single static HTML file, it can be deployed as-is to any
static host (GitHub Pages, Netlify, Vercel, S3, etc.) — just publish this
folder, or rename/copy `index.html` to wherever the host expects an entry
point.

This is a **concept/preview page only** — a slim banner at the top of the
page marks it as such. Remove that banner before using it as a live site.
