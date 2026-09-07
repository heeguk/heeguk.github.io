# heeguk.github.io

Personal portfolio site. Static, no build step: `index.html` is self-contained.

Live at <https://heeguk.github.io/>

## Deploy

GitHub Pages serves this repo from `main` / root. Publishing is just:

```bash
git add -A && git commit -m "..." && git push
```

Pages rebuilds automatically; progress shows in the repo's Actions tab.

One-time setup: Settings -> Pages -> Source `Deploy from a branch`,
Branch `main` / `/ (root)`.

## Local preview

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Notes

- Only external dependency is Google Fonts (Archivo, Azeret Mono).
- Light and dark themes both supported via `prefers-color-scheme`.
- Architecture diagrams are sanitized; proprietary names, configuration,
  and data are omitted.
