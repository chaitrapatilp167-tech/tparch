# Atelier North — Architecture Studio Website

A responsive six-page frontend for a fictional architecture and interiors studio. Built with plain HTML, CSS, and JavaScript; no build step or dependencies are required.

## Pages

- `index.html` — Home
- `about.html` — About the studio
- `projects.html` — Project gallery with category filters
- `services.html` — Architecture, interiors, and advisory services
- `insights.html` — Studio journal
- `contact.html` — Contact details and inquiry form

## Run locally

Open `index.html` in a browser, or serve this folder with any static web server. For example, with Python installed:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

The contact form opens a pre-filled email in the visitor’s default email app. Photos are bundled locally in `images/` as distinct files, so the photography works offline. Web fonts still load from Google Fonts when online.
