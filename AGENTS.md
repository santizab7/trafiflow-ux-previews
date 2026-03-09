# AGENTS.md

## Cursor Cloud specific instructions

This is a static HTML project with no build system, package manager, or runtime dependencies. All CSS and JS are inlined in the HTML files.

### Running the dev server

Serve files locally with Python's built-in HTTP server:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080/` to view the hub page linking to the 4 landing page variants (Cobalt, Void, Signal, Market).

### Project structure

- `index.html` — Hub page linking to all variants
- `cobalt.html` — "Electric Blue" cyberpunk neon variant
- `void.html` — "Deep Purple" minimal deep-space variant
- `signal.html` — "Electric Teal" terminal/dashboard variant
- `market.html` — "Clean Commerce" Shopify-style white variant

### Notes

- No lint, test, or build commands exist. There are no `package.json`, `Makefile`, or CI config files.
- The only external resource is Google Fonts loaded via CDN `<link>` tags; no network access issues will affect core rendering.
- Any static file server works (e.g. `npx serve`, VS Code Live Server, `python3 -m http.server`).
