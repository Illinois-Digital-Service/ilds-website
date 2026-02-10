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

## Development

Key files and folders:

- `_config.yml` - Site configuration
- `index.md` - Homepage content
- `_layouts/` - HTML templates
- `_includes/` - Reusable components

## Deployment

This site is configured for GitHub Pages and will automatically build and deploy when changes are pushed to the repository's `main` branch.
