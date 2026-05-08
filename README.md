# Playable Portfolio

Static landing page for the playable demos under [@tassiost](https://github.com/tassiost). Deployed via GitHub Pages.

Live: <https://tassiost.github.io/portfolio/>

## What this is

A single-file `index.html` listing the live games and AI-powered tools, with **Play** / **Code** buttons. Hosted on GitHub Pages so the share link has no cold-start.

## Editing

Edit `index.html`, push to `main`, GitHub Pages rebuilds in ~30 seconds.

## Adding a new project

1. Add a new `<article class="card">` block under the "Playable now" or "Coming soon" grid.
2. Set the icon emoji, name, tagline, description, and links.
3. Use `<span class="pill live">live</span>` for shipped, `<span class="pill soon">…</span>` for in-progress.

## Source content

Project descriptions are derived from `Manager/TEAM_PORTAL.md` (private operator workspace).
