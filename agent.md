# Agent Context

## Project Overview
Static personal art portfolio hosted on GitHub Pages. The site is a set of hand-authored HTML files that use Tailwind CSS via CDN, Google Fonts, and Font Awesome. Images live in the `images/` folder.

## Tech Stack
- Static HTML
- Tailwind CSS via CDN (`https://cdn.tailwindcss.com`)
- Google Fonts
- Font Awesome
- GitHub Pages (CNAME at repo root)

## Repository Layout
- `index.html`: Personal illustrations grid
- `academic.html`: Academic work
- `about.html`: About page
- `contact.html`: Contact page
- `illustrations.html`: Additional illustration page (if used)
- `images/`: Artwork and logo assets
- `CNAME`: Custom domain for GitHub Pages

## Working Notes
- No build step; edit HTML files directly.
- Keep paths relative (GitHub Pages).
- Prefer minimal JS; styling is handled with Tailwind utility classes.
- Images are linked directly and opened in new tabs.

## Common Tasks
- Update navigation consistently across all pages.
- Add new artwork by placing files in `images/` and adding corresponding `<img>` entries in the relevant HTML page.
- Keep `alt` text meaningful for accessibility.
