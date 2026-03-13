# Ian Connors – Online Resume

This is a single-page, static online resume for **Ian Connors**, focused on cloud, infrastructure, networking and security engineering.

It is built as a lightweight HTML/CSS site so it can be hosted easily on static hosting platforms (GitHub Pages, Netlify, Azure Static Web Apps, etc.).

## Structure

- `index.html` – main page layout and content.
- `styles.css` – visual design (dark theme, glassmorphism-style cards, responsive grid).
- `package.json` – minimal metadata and a convenience script for local preview.

## Local development

From the `Resume` directory:

```bash
npm install
npm run start
```

The `start` script will use `serve` (via `npx`) to host the current directory. You can also open `index.html` directly in a browser without any tooling.

## Deployment

Any static hosting solution can serve this site. The only requirement is that `index.html` is the entry point and `styles.css` is served alongside it.

