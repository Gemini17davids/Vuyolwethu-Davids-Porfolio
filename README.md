# Personal Portfolio

A clean, elegant, single-page portfolio. No build step, no dependencies — just HTML, CSS and a little JavaScript.

## Structure

```
portfolio/
├── index.html
├── css/style.css
├── js/main.js
└── assets/favicon.svg
```

## Run it

Open `index.html` in your browser. That's it.

## Make it yours

- **Text & links:** edit `index.html` (name, bio, projects, experience, email, social links).
- **Colours & fonts:** edit the variables at the top of `css/style.css` (`--accent`, `--bg`, `--serif`, ...).
- **Project images:** replace each `<div class="thumb thumb-N">` in `index.html` with
  `<img src="assets/your-image.jpg" alt="Project name" />` and style it with the same `.thumb` size.
- **Favicon:** replace `assets/favicon.svg`.

## Features

- Light and dark mode (remembers the visitor's choice, follows system preference by default)
- Responsive layout for phones, tablets and desktops
- Soft reveal-on-scroll animations (disabled for visitors who prefer reduced motion)
- Accessible: semantic markup, focus styles, keyboard friendly

## Deploy

Upload the folder to any static host: Netlify, Vercel, GitHub Pages or Cloudflare Pages.
