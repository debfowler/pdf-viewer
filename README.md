# PDF Tab Viewer

A single-file browser tool for flipping through a batch of PDFs — no installs, no uploads, everything stays local.

**[Live Demo →](https://YOUR-USERNAME.github.io/pdf-viewer/)** *(update after deploying)*

---

## Features

- Open 1–100+ PDFs at once (drag & drop or file picker)
- Click tabs or use **← →** arrow keys to navigate
- `Home` / `End` keys jump to first/last
- All files are opened locally in your browser — nothing is uploaded anywhere
- Works in Chrome, Edge, and Firefox

## Usage

### Option A — GitHub Pages (recommended)

1. Fork or clone this repo
2. Go to **Settings → Pages → Source → main branch / root**
3. Visit `https://YOUR-USERNAME.github.io/pdf-viewer/`

### Option B — Run locally

Just open `index.html` in your browser. That's it.

> **Note:** Some browsers block local file access when opening `index.html` directly from disk.  
> If PDFs don't load, serve it with a simple local server:
> ```bash
> npx serve .
> # or
> python3 -m http.server 8080
> ```

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `→` or `↓` | Next PDF |
| `←` or `↑` | Previous PDF |
| `Home` | First PDF |
| `End` | Last PDF |

## Privacy

All processing happens in your browser. No files are uploaded. No data is sent anywhere.
