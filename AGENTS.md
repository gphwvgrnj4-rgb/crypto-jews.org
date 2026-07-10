# crypto-jews.org

Placeholder repository for a static website. Currently `index.html` is empty; content will be a single self-contained static HTML file like the sibling `*.org` repos. There is no build step, package manager, dependency install, lint, or test suite.

## Cursor Cloud specific instructions

- Static site, no dependencies to install. Python 3 and Node are preinstalled; nothing is needed to develop or run it.
- Run locally with a static file server from the repo root: `python3 -m http.server 8000`, then open `http://localhost:8000/`.
- `index.html` is currently empty (placeholder), so the served page will be blank until content is added.
- "Building" just means opening the static file in a browser; there is no lint or automated test tooling.
