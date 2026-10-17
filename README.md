# manakame

This repository contains a static website for the manakame profile.

## Local preview

Open `index.html` in a browser, or run a simple local web server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages + custom domain

To publish the site on `https://manakame.ru`, make sure your DNS points the root domain to GitHub Pages and that the repository has Pages enabled.

The `CNAME` file already contains:

```text
manakame.ru
```

For full setup, enable GitHub Pages in the repository settings and select the `main` branch (root folder).
