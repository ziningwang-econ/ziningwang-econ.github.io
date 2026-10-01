# Zining Wang — Academic Website

Personal academic website of Zining Wang, a Ph.D. candidate in Economics at the Guanghua School of Management, Peking University. Built with Hugo and HugoBlox Academic CV, and configured for GitHub Pages deployment.

## Edit the website

- `data/authors/me.yaml`: biography, email, and education.
- `content/_index.md`: homepage layout.
- `content/research.md`: publications and working papers.
- `config/_default/menus.yaml`: navigation. CV is currently disabled; remove `params.disabled` and add a URL when the CV is ready.
- `assets/css/custom.css`: custom styles.
- `layouts/_partials/components/headers/navbar.html`: navigation template supporting disabled items.

## Local preview

Requires Hugo, Go, Node.js, and pnpm. Install the frontend dependencies once:

```sh
pnpm install --frozen-lockfile
```

Start the preview:

```sh
HUGO_MODULE_PROXY=https://goproxy.cn pnpm dev --cacheDir /private/tmp/zining-hugo-cache-cn
```

Open http://127.0.0.1:1313/ in a browser. Hugo rebuilds and refreshes the page when files change. Press Ctrl+C to stop.

`config/development/security.yaml` allows the installed Tailwind CLI during local development.

## Deployment

The GitHub Actions workflow builds and deploys the site when changes are pushed to `main`. Production settings are in `hugoblox.yaml` and `config/_default/`.

HugoBlox dependencies and their attribution remain in place. See `LICENSE.md` for the project license.
