# Illicit Networks Workshop

Website for the [Illicit Networks Workshop](https://illicitnetworksworkshop.com) (INW), an academic conference series bringing together scholars and analysts working on network analysis of organised crime, terrorism, corruption, and related topics.

## Structure

- `/2026/` — Current edition (Vienna, Austria)
- `/2024/` through `/2010/` — Archive pages for past editions
- `/index.html` — Redirects to the current edition

## Local Development

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000/2026/](http://localhost:8000/2026/).

A local server is required because pages use absolute paths that won't resolve with `file://` URLs.

## Hosting

Static site hosted on [GitHub Pages](https://pages.github.com/) with a custom domain configured via `CNAME`.
