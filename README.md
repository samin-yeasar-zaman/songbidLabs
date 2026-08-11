# Songbid — Portfolio

A modern, dark-themed developer portfolio built with semantic HTML5, CSS3 and vanilla JavaScript.

🔗 **Live demo:** _add your deployed link here_

![Portfolio screenshot](assets/screenshots/homepage.png)
_Add a screenshot or GIF of the finished site to `assets/screenshots/` and update the path above._

## Features
- Responsive layout (mobile / tablet / desktop breakpoints at 576px and 991px)
- Sticky, collapsible navbar with mobile menu
- Scroll-triggered fade-in animations (respects `prefers-reduced-motion`)
- Animated typewriter role in the hero section
- Hover-interactive project and skill cards
- Semantic, accessible markup (skip-friendly headings, `aria-*` attributes, visible focus states)

## Built with
- HTML5
- CSS3 (custom properties, Grid, Flexbox — no framework)
- Vanilla JavaScript
- [Font Awesome](https://fontawesome.com/) for icons
- Google Fonts — Poppins, Inter, JetBrains Mono

## Getting started
```bash
git clone https://github.com/yourusername/portfolio.git
cd portfolio
```
Then open `index.html` in your browser — no build step required.

## Folder structure
```
portfolio/
├── index.html
├── css/
│   ├── style.css        # design tokens, layout, components
│   └── responsive.css   # breakpoints
├── js/
│   └── script.js        # nav toggle, scroll animations, typewriter
├── assets/
│   ├── images/
│   ├── icons/
│   ├── fonts/
│   └── screenshots/      # for this README
└── README.md
```

## Customizing
- **Content:** replace the placeholder name, bio, skills, project details and contact links throughout `index.html`.
- **Colors/spacing:** all design tokens live at the top of `css/style.css` under `:root`.
- **Project images:** swap `assets/images/project-placeholder.svg` for real screenshots.

## What I learned
_Short, honest reflection — what surprised you, what you'd do differently, or a specific problem you solved while building this._

## License
MIT
