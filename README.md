# ArmPi mini Documentation

This repository contains the ArmPi mini VitePress documentation site. The
documentation source files are Markdown files under `docs/docs/`.

## Local development

Install dependencies and start the local documentation server:

```bash
npm ci
npm run docs:dev
```

Build the production site:

```bash
npm run docs:build
```

The production files are generated in `docs/.vitepress/dist/`.

## GitHub Pages deployment

Build and stage the static files before pushing:

```bash
npm run docs:build
npm run docs:stage-main
```

Commit the generated `projects/` directory, then configure GitHub Pages with
**Deploy from a branch**, **main**, and **/(root)**. The GitHub Pages URL is:

```text
https://hiwonder-docs.github.io/ArmPi-mini-vite/projects/ArmPi_mini/en/latest/
```

When the wiki reverse proxy is configured, the same site path becomes:

```text
https://wiki.hiwonder.com/projects/ArmPi_mini/en/latest/
```
