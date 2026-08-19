# AC Service Field Guide

A static, mobile-friendly AC option-code and error-code reference.

## GitHub Pages deployment

The website entry point is [`index.html`](index.html). Every push to `main` runs [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml) and publishes it to GitHub Pages. The workflow can also be started manually from the repository's **Actions** tab.

One-time repository setup:

1. Open **Settings → Pages** in GitHub.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push this workflow to `main` and watch the **Deploy to GitHub Pages** run in the **Actions** tab.

After a successful deployment, the site will be available at:

<https://kamkyi.github.io/error-code/>
