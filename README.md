<div align="center">

# 🎨 HTML & CSS Template Collection

### Four responsive front-end builds in one small repository

*Portfolio, survey form, tribute page and product landing page — built with plain HTML and CSS.*

<p>
  <img src="https://img.shields.io/badge/HTML5-Markup-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Responsive-Layouts-brightgreen?style=for-the-badge" alt="Responsive">
</p>

</div>

---

## 📖 Overview

A set of static front-end pages that double as starter templates. Each page focuses on a different layout pattern: a personal portfolio, a form, a tribute article and a product landing page. No framework, no build step — just open the HTML in a browser.

## 📂 What is inside

| Page | Stylesheet | Description |
|:--|:--|:--|
| `main.html` | `styles4.css` | Personal portfolio with sticky navigation, hero section, project grid and contact area. |
| `survey.html` | `styles.css` | Survey form with text, email, number, dropdown, radio and checkbox inputs. |
| `apj.html` | `styles1.css` | Tribute page with an image block, biography and external reference link. |
| `ss.html` | `styles3.css` | SunShield Pro product landing page with feature cards, pricing and a fixed header. |

## ✨ Highlights

- 📱 Responsive layouts using Flexbox and CSS Grid.
- 🧼 Clean, semantic HTML5 structure.
- 🎨 Separate stylesheets for each page, easy to copy into a new project.
- 🔗 Font Awesome icons on the portfolio page.
- ♿ Form labels and input types that work with browser validation.

## 🚀 Getting started

### Option 1 — open directly

Double-click any HTML file, or drag it into a browser tab.

### Option 2 — serve locally

```bash
# from the repository folder
python -m http.server 8000
```

Then open `http://localhost:8000/main.html` (or any of the other pages).

## 🗂️ Project structure

```text
description_template/
├── main.html        # Portfolio
├── survey.html      # Survey form
├── apj.html         # Tribute page
├── ss.html          # Product landing page
├── styles.css       # Survey form styles
├── styles1.css      # Tribute page styles
├── styles3.css      # Landing page styles
└── styles4.css      # Portfolio styles
```

## ⚠️ Before publishing

- Images are loaded from external Bing URLs. Replace them with your own assets for a production site.
- Some links in `main.html` point to local `file:///` paths. Update them to relative paths or live URLs.
- The tribute page and landing page are demo layouts — swap in your own content and branding.

## 🧰 Built with

| Layer | Tools |
|:--|:--|
| Structure | HTML5 |
| Styling | CSS3 (Flexbox, Grid, media queries) |
| Icons | Font Awesome |
| Tooling | None — plain static files |

## 🛣️ Possible next steps

- [ ] Add a shared `styles/base.css` for common resets and variables.
- [ ] Replace remote images with local assets.
- [ ] Add a simple index page linking to all four templates.
- [ ] Deploy the collection with GitHub Pages.

---

<div align="center">

**Good design is invisible; good templates save time. ✨**

</div>