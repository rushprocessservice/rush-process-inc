# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository Overview

This is a minimal static redirect repository containing a single HTML file that redirects to https://www.rushprocessservice.com/. The repository serves as a GitHub Pages redirect from the `rush-process-inc` domain to the main website.

## Structure

- `_config.yml` - Jekyll configuration enabling the redirect plugin
- `index.md` - Jekyll markdown file with redirect front matter

## Working with this Repository

This repository uses Jekyll (built into GitHub Pages) with the `jekyll-redirect-from` plugin for SEO-friendly redirects.

To modify the redirect target:
1. Edit `index.md`
2. Update the `redirect_to` URL in the front matter

GitHub Pages automatically builds and deploys Jekyll sites when changes are pushed to the main branch.
