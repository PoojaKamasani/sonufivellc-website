# Sonufive LLC — Official Website

The official website for **Sonufive LLC** — Neighborhood Spirits. Two Stores. One Family.

🌐 **Live site:** [sonufivellc.com](https://sonufivellc.com)

## About

This is the public-facing website for Sonufive LLC, a family-owned neighborhood spirits business operating two retail locations.

## Tech Stack

- **Static HTML5 / CSS3 / JavaScript** — no framework, no build step
- **Hosted on GitHub Pages** with custom domain
- **Fonts:** Cormorant Garamond, Inter, JetBrains Mono (via Google Fonts)

## Project Structure

```
.
├── index.html          # Main landing page
├── CNAME               # Custom domain for GitHub Pages
├── assets/
│   └── photos/         # Store interior/exterior photography
├── screenshots/        # Mobile preview images
└── uploads/            # Additional image uploads
```

## Local Development

This is a pure static site — no build step required. To preview locally:

```bash
# Option 1: Python 3
python3 -m http.server 8000

# Option 2: Node.js (with npx)
npx serve .
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

## Deployment

Any push to the `main` branch is automatically published to [sonufivellc.com](https://sonufivellc.com) via GitHub Pages.

## License

© Sonufive LLC. All rights reserved.
