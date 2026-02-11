# Illinois Digital Service Website

A Jekyll-based website for Illinois Digital Service, configured for GitHub Pages.

## About

Illinois Digital Service works shoulder-to-shoulder with Illinois government agencies to deliver better technology, faster. Our mission is to make Illinois public technology friendly to use for everyone who lives here.

## Prerequisites

- Ruby (version 3.3 or higher)
- Bundler gem

## Setup

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

3. Open your browser to `http://localhost:4000`

## Accessibility scan

The repo runs an accessibility scan (Pa11y CI, WCAG 2 AAA) in CI on pull requests. You can run the same scan locally anytime.

**Prerequisites:** Node.js (e.g. v20) and npm.

1. Install Pa11y CI once:
   ```bash
   npm install -g pa11y-ci
   ```

2. Build and serve the site (the scan expects it at `http://127.0.0.1:4000`):
   ```bash
   bundle exec jekyll build
   cd _site && python3 -m http.server 4000
   ```
   Leave that server running in one terminal.

3. In another terminal, from the project root, run the scan:
   ```bash
   pa11y-ci
   ```

## Development

Key files and folders:

- `_config.yml` - Site configuration
- `index.md` - Homepage content
- `_layouts/` - HTML templates
- `_includes/` - Reusable components

## Deployment

This site is configured for GitHub Pages with two workflows:

- **Production** (`.github/workflows/production-deploy.yml`) — Runs on push to `main`. Deploys the live site to the repository’s GitHub Pages site (e.g. `https://illinoisdigitalservice.org`).
- **Preview** (`.github/workflows/preview-build.yml`) — Runs on push to any non-`main` branch (and via workflow_dispatch). Builds the branch and deploys it alongside the current production site so that production stays at `/` and the branch preview is available at a single, stable URL: **https://illinoisdigitalservice.org/preview-deploy/**.

Only one deployment (production or preview) runs at a time; they share a concurrency group (`pages-deploy`) so that each run completes without being cancelled. Because each deployment replaces the entire site, there is ever only **one** preview live at a time — the most recently built branch. The preview URL is always the same; you don’t need a different path per branch.
