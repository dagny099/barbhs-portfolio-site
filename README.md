# barbhs portfolio site

Static portfolio site for Barbara Hidalgo-Sotelo, deployed on **Netlify** at
[https://portfolio.barbhs.com](https://portfolio.barbhs.com).

## Files

| File           | Purpose                                                                 |
| -------------- | ----------------------------------------------------------------------- |
| `index.html`   | Homepage — projects overview. Served at the site root `/`.              |
| `graph.html`   | Interactive knowledge graph of projects. Linked from the homepage.      |
| `og-portfolio.png` | Open Graph / social preview image.                                  |

> **Note:** Netlify serves `index.html` at the root URL. The homepage must be
> named `index.html` (not `portfolio.html`) or the root will 404.

## Deployment

Deploys automatically via the connected GitHub repo. Every push to `main`
triggers a new Netlify build — no build command needed, since the site is
plain static HTML published from the repo root.

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```
