# HTML Viewer

A free, client-side HTML viewer and playground: paste or type HTML code and see a live rendered preview instantly — all in a single self-contained HTML file. No sign-up, no backend, no build step.

Live demo: https://girishlade111.github.io/HTML-Viewer/

## Features

- **Live preview** — renders HTML/CSS/JS in real time in an embedded preview pane
- **Code editor** — CodeMirror-powered editing with HTML/CSS/JS syntax highlighting
- **Format HTML** — one-click code formatting
- **Drag & drop** — drop an `.html` file to load it into the editor
- **Copy & download** — copy code to clipboard or download it as a file
- **Theme toggle** — light/dark editor themes
- **Error display** — inline error feedback when something goes wrong
- **100% client-side** — your code never leaves the browser

## Tech stack

- Plain HTML, CSS, JavaScript (single file, no build step)
- CodeMirror 5 (CDN) for the code editor

## Quick start

Option 1 — open the live demo in your browser (link above).

Option 2 — run locally:

```bash
git clone https://github.com/girishlade111/HTML-Viewer
# open index.html (or html-viewer-webapp.html) in any browser
```

That's it — no `npm install`, no server, no configuration.

## Project structure

```
.
├── index.html               # Entry point (same app as html-viewer-webapp.html)
├── html-viewer-webapp.html  # The full app: editor + live preview
├── README.md
└── LICENSE
```

## Deploy

Static hosting — the app is a single HTML file:

- **GitHub Pages** (current live deployment): served from the repo root via the Pages API
- Any static host (Netlify, Cloudflare Pages, Vercel): drag-and-drop the repo folder

## Built by Girish Lade

Created by [Girish Lade](https://ladestack.in) — free, no-login, local-first tools.
