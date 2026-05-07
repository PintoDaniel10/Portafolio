# AGENTS.md

## Project Type
Static portfolio website using HTML + Tailwind CSS v4 (CDN) + Vanilla JavaScript

## Commands
- Serve locally: Open `index.html` in browser or use `npx serve`
- No build step, tests, or npm scripts

## Tech Stack
- **Tailwind CSS v4** via CDN with custom theme config
- **Font Awesome 6** for icons (CDN)
- **Google Fonts**: Inter + JetBrains Mono
- **Vanilla JavaScript** (no jQuery, no frameworks)

## Key Files
- `index.html` - Main page with all sections
- `js/main.js` - Navigation, dark mode toggle, back-to-top, scroll spy
- `css/style.css` - Legacy file (deprecated, styles in Tailwind via CDN)

## Design Features
- Dark mode with system preference detection + manual toggle
- Responsive (mobile-first)
- Custom colors: primary (#6195FF), dark (#10161A), gray (#868F9B)
- Glass morphism navbar, gradient overlays, card hover animations
