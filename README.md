# Quiver website

Source for **<https://quiveride.github.io/>** — the landing page for **Quiver**,
a desktop **session manager for Claude Code & Codex**.

Quiver gives every terminal coding-agent session — Claude Code, Codex, and more
on the way — a window of its own: pinned and searchable across projects, local
or over SSH, with the real terminal, real git diff, per-block staging, and a
real shell in one frame.

- **Download / releases:** <https://github.com/quiveride/quiver-releases/releases>
- **Issues & ideas:** <https://github.com/quiveride/quiver-releases/issues>

## This repo

A static site served by GitHub Pages from `main` (root) — no build step:

- `index.html` — English landing page
- `zh/index.html` — 中文版
- `assets/` — screenshots and images
- `sitemap.xml` — submitted to Search Console

The app source lives in the private `quiveride/quiver` repo; release binaries
live in the public [`quiveride/quiver-releases`](https://github.com/quiveride/quiver-releases).
