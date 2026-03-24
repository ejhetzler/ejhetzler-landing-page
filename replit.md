# Ethan Hetzler — Personal Landing Page

## Overview

A static, single-page professional landing page for Ethan Hetzler, a University of Iowa Tippie College of Business student entering financial advising at Equitable Advisors in Kansas City.

## Stack

- **Language:** HTML5 + CSS3 (vanilla — no frameworks, no JavaScript framework)
- **Server (dev):** Python 3 built-in HTTP server (`python3 -m http.server 5000`)
- **Deployment:** Static site (root directory served directly)

## Project Structure

```
/
├── index.html           # Single-page site
├── css/
│   └── stylesheet.css   # All styles (no inline styles)
├── js/
│   └── scripts.js       # Smooth-scroll only
├── images/
│   └── headshot.jpg     # Ethan's professional headshot (add this file)
├── prd.md               # Product requirements document
├── standards.md         # Technical and design standards
└── replit.md            # This file
```

## Running Locally

The workflow "Start application" serves the site on port 5000:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Key Notes

- All styles live in `css/stylesheet.css` — no inline `style=""` attributes anywhere.
- The headshot image must be placed at `images/headshot.jpg` — the `<img>` tag references it by relative path.
- Color palette: Navy/teal (`#0d5c8a`) accent, `#f8f9fa` background, `#212529` body text.
- Font: Inter (loaded from Google Fonts).
- Fully responsive from 320px wide; no horizontal scroll.
- WCAG 2.2 Level AA accessibility standards applied throughout.
- All external links open in a new tab with `rel="noopener noreferrer"`.

## Adding the Headshot

Place Ethan's headshot at `images/headshot.jpg`. The image will display as a 160px circular crop in the hero section.

## Deployment

Configured as a static site deployment (root directory). Click Publish to make it live on a `.replit.app` domain.
