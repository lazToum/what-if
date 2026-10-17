# what-if.io

The site at [what-if.io](https://what-if.io): a small placeholder while something new is
built.

## Layout

```
site/        static files published as-is (index.html, style.css, app.js, 404.html)
.github/     Pages deploy workflow
```

## Run locally

```bash
python3 -m http.server -d site 8000   # http://localhost:8000
```

## Deploy

Every push to `main` publishes `site/` to GitHub Pages. The custom domain is set in the
repository's Pages settings.

## License

[Apache 2.0](LICENSE). © 2026 Lazaros Toumanidis.
