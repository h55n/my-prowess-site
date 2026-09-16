# PROWESS — Experimental Creative Web Experience

PROWESS is a single-page visual web experiment focused on bold editorial typography, kinetic motion, a custom cursor, and a high-contrast red/black art direction.

The project is intentionally lightweight: the full experience lives in `index.html` and loads React, Babel, and Tailwind from CDNs rather than using a bundler or application framework.

## Highlights

- React 18 rendered directly in the browser
- Tailwind CSS via CDN
- Babel standalone for JSX
- Custom animated cursor
- Scroll-reactive typography and motion
- Responsive single-page composition
- Bodoni Moda / Inter / Antonio typography

## Run locally

No build step is required.

```bash
git clone https://github.com/h55n/my-prowess-site.git
cd my-prowess-site
python -m http.server 8080
```

Then open `http://localhost:8080`.

You can also open `index.html` through VS Code Live Server or any other static-file server.

## Repository structure

```text
my-prowess-site/
├── .github/
├── index.html      # Entire React/Tailwind experience
└── README.md
```

## Project scope

This is a creative/front-end study rather than a production application. It is useful as a compact showcase of visual direction, typography, browser animation, and interaction design.
