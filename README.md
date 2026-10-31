# Portfolio Website

Personal portfolio/resume site for Skylar Knapp. Static HTML/CSS/JS, no build step, deploys to GitHub Pages.

## Structure
- `index.html` — all page content
- `css/styles.css` — design system (colors, type, layout) as CSS variables
- `js/main.js` — mobile nav toggle, footer year
- `assets/` — resume PDF and project screenshots go here

## To do before this goes live
- [ ] Replace the `<!-- EDIT ME -->` placeholders in `index.html` (bio, project links, GitHub link)
- [ ] Add `assets/resume.pdf`
- [ ] Add real screenshots for each project card (optional — text-only cards work fine too)
- [ ] Push to GitHub, enable GitHub Pages in repo settings (Settings → Pages → deploy from `main` branch)

## Local preview
Open `index.html` directly in a browser, or run a tiny local server from this folder:

    npx serve .
