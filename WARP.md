# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository Overview

This is a minimal static redirect repository containing a single HTML file that redirects to https://www.rushprocessservice.com/. The repository serves as a GitHub Pages redirect from the `rush-process-inc` domain to the main website.

## Structure

- `index.html` - Simple HTML redirect file with meta refresh and canonical link

## Working with this Repository

Since this is a static redirect repository with minimal code, there are no build processes, test suites, or complex development workflows.

To modify the redirect target:
1. Edit `index.html`
2. Update the URL in the `<meta http-equiv="refresh">` content attribute
3. Update the URL in the `<link rel="canonical">` href attribute
4. Update the `<title>` tag to reflect the new destination

The repository likely uses GitHub Pages for hosting. Changes pushed to the main branch will automatically deploy.
