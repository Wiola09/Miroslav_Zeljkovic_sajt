# Miroslav Zeljković — Personal Portfolio

A clean, responsive static portfolio site showcasing my background as an Electrical Engineer and Python developer. Built with vanilla HTML, CSS, and JavaScript and hosted on GitHub Pages.

---

## Overview

This single-page portfolio presents:

- **Profile** — Short intro and professional focus (Python development, continuous learning)
- **Skills** — Programming, Python development, and front-end technologies (HTML5, CSS3, JavaScript)
- **Contact** — Call-to-action for freelance work and collaboration

The design uses a light, readable layout with custom typography (Google Fonts: Merriweather, Montserrat, Sacramento) and a teal/cyan color palette. The layout is responsive and adapts to smaller screens.

---

## Tech Stack

| Layer      | Technology                          |
| ---------- | ------------------------------------ |
| Markup     | HTML5                                |
| Styling    | CSS3 (custom properties, flexbox, media queries) |
| Scripting  | Vanilla JavaScript (minimal, e.g. dynamic year in footer) |
| Fonts      | Google Fonts (Merriweather, Montserrat, Sacramento) |
| Hosting    | GitHub Pages (static site)           |

No build tools or frameworks — plain static files only.

---

## Project Structure

```
.
├── index.html          # Single-page content
├── css/
│   └── styles.css      # Global styles and responsive rules
├── images/             # Assets (profile photo, icons, illustrations)
├── favicon.ico
├── CNAME               # Custom domain for GitHub Pages
└── README.md
```

---

## Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Open `index.html` in a browser, or serve the folder with any static server, for example:
   ```bash
   # Python 3
   python -m http.server 8000

   # Node (if you have npx)
   npx serve .
   ```
   Then visit `http://localhost:8000` (or the port shown).

---

## Custom Domain (GitHub Pages)

If you use a custom domain, add it to the `CNAME` file. Configure DNS as described in [GitHub Pages custom domain documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

---

## License

All rights reserved.
