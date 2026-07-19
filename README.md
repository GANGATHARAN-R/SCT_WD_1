# Task 01 — Responsive Landing Page

## Objective
Create an interactive navigation menu that changes color/style on scroll and on hover.
The menu is fixed in position and visible across the whole page.

## Features
- **Fixed navbar** — stays at the top using `position: fixed`
- **Scroll effect** — navbar background changes from transparent to solid dark once the user scrolls past 50px (handled in `js/script.js`)
- **Hover effect** — nav links change color and get an animated underline on hover
- **Responsive** — collapses into a hamburger menu below 768px screen width

## File Structure
```
responsive-landing-page/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── README.md
```

## How to Run
1. Download or clone the repo
2. Open `index.html` in any browser
3. Scroll down to see the navbar change style
4. Hover over the nav links to see the hover effect
5. Resize the browser (or open on mobile) to test the hamburger menu

## Tech Used
- HTML5
- CSS3 (Flexbox, transitions, media queries)
- Vanilla JavaScript (scroll event + class toggling)
