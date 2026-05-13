# fawraw.github.io

Personal landing site for [Farid Said](https://github.com/fawraw), hosted on GitHub Pages at <https://fawraw.github.io/>.

Static HTML + CSS. No build step, no framework, no JavaScript. `.nojekyll` to skip Jekyll processing.

## Local preview

```bash
python3 -m http.server 8080
open http://localhost:8080/
```

## Files

- `index.html`: the page
- `style.css`: dark / light theme via `prefers-color-scheme`, ~150 lines
- `.nojekyll`: tell GitHub Pages to serve files as-is

## License

MIT. See [LICENSE](LICENSE).
