# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static website for Zerzius Asset Management S.L. - a private holding company focused on long-term investment management. The site is hosted on GitHub Pages at www.zerzius.com.

## Architecture

Bilingual static site consisting of:
- `index.html` - Spanish version (default)
- `index_en.html` - English version
- `logo1_zerzius.png` - Company logo
- `CNAME` - GitHub Pages custom domain configuration

Both HTML files contain inline CSS and minimal JavaScript. No build process, dependencies, or external tooling required.

## Development

To preview locally, open `index.html` directly in a browser or use any static server:
```bash
python3 -m http.server 8000
```

## Deployment

Push to `main` branch triggers automatic GitHub Pages deployment.

## Design System

CSS variables are defined in `:root` within the HTML files. Fonts: Ubuntu Mono for branding elements, system fonts for body text.
