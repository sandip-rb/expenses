# Kharcha UI

This repository hosts the built frontend for [Kharcha](https://github.com) - a personal expense management app.

**This repo is auto-deployed.** Do not edit files here directly — they are overwritten on every push to the source repository's `main` branch.

## How it works

1. Code is pushed to the private `kharcha` repo
2. GitHub Actions builds the Vite/React app
3. The `dist/` output (with `index.html` + `404.html` for SPA routing) is force-pushed here
4. This repo's GitHub Pages workflow deploys the assets to the live site

## Setup

In the GitHub repo settings:
- **Pages** → Source: GitHub Actions
