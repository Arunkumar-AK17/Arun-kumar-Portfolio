# Arun Portfolio

## Run locally
1. Install Node.js (LTS).
2. Open this folder in VS Code.
3. Run `npm install`.
4. Run `npm run dev`.

## GitHub Pages
This project is configured for a GitHub repository named `arun-portfolio`.
Push the project to the `main` branch, then open Settings → Pages and select
**GitHub Actions** as the deployment source. The workflow in `.github/workflows/deploy.yml`
builds the Vite project and deploys the `dist` folder.

If your repository has a different name, update `base` in `vite.config.js`
to `/<repository-name>/`.
