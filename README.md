# Week 2: CSS Mastery — Portfolio

**Author:** Manu-debug-hub
**Repository name (per guidelines):** `iyf-s11-week-02-manu-debug-hub`

## What's included

| File | Covers |
|---|---|
| `styles.css` | Reset, typography system, color system, nav, hero, cards, grid, footer, responsive breakpoints |
| `index.html` | Home page — hero + focus-area cards (Flexbox card row) |
| `about.html` | About page — magazine-style CSS Grid layout (Task 4.2 Ex. 2) |
| `projects.html` | Projects page — photo gallery grid (Task 4.2 Ex. 1) + responsive project cards grid (1→2→3 columns) |
| `contact.html` | Contact page — form + sidebar layout |
| `box-model-practice.html` | Task 3.2 — box model visualization, debugged 300px box, spec card |
| `script.js` | Mobile hamburger menu toggle |

## Task checklist

- [x] 3.1 CSS reset, base typography, heading styles
- [x] 3.2 Box model visualization, debug exercise (fixed with `box-sizing: border-box`), spec'd card component
- [x] 3.3 Type scale using CSS custom properties, heading font (JetBrains Mono) + body font (Inter)
- [x] 3.4 Color system using CSS custom properties, applied to headings/text/links/buttons/backgrounds
- [x] 4.1 Flexbox nav bar, card row (wraps, equal height), footer with 3 columns + centered copyright
- [x] 4.2 Photo gallery grid, magazine layout, responsive project cards grid
- [x] 4.3 Mobile-first breakpoints at 768px / 1024px / 1280px; hamburger nav on mobile
- [x] 4.4 Hover states, transitions, focus states for accessibility

## How to view locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

## Submitting to GitHub

```bash
git init
git add .
git commit -m "Week 2: CSS Mastery - responsive portfolio"
git branch -M main
git remote add origin https://github.com/Manu-debug-hub/iyf-s11-week-02-manu-debug-hub.git
git push -u origin main
```