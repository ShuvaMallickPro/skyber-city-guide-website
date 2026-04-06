# SKYBER — City Guide Website Template

A responsive, multi-page city guide website template built with **HTML**, **Sass (SCSS)**, **Bootstrap 5**, and **vanilla JavaScript**.

- **Live demo**: [View on GitHub Pages](https://ShuvaMallickPro.github.io/skyber-city-guide-website/)
- **GitHub Repository**: [View repository](https://github.com/ShuvaMallickPro/skyber-city-guide-website)

## Overview

SKYBER is a modern UI template for city guides / local directories. It includes ready-to-use pages for catalog browsing, place details, accounts, vendor flows, and content pages (blog, help center, etc.). Styles are authored in SCSS and compiled into `dist/css`.

## Tech stack

- **HTML5**
- **Sass (SCSS)**
- **Bootstrap 5**
- **JavaScript (vanilla)**
- **Swiper** (sliders)
- **noUiSlider** (range slider)
- **GLightbox** (lightbox)
- **Google Fonts** + **Font Awesome** (icons)

## Key features

- **Responsive layout** (mobile, tablet, desktop)
- **Reusable Bootstrap components** (navbar, modals, cards, forms, etc.)
- **SCSS-based styling** for easier customization and maintainability
- **Interactive UI** (sliders, filters/range slider, gallery lightbox, account modals)
- **Multi-page structure** ready for real content integration

## Pages included

- **Home** (`index.html`)
- **Catalog**
  - Categories & Filters (`catalog-categories-filters.html`)
  - Single Place: Gallery (`catalog-single-place-gallery.html`)
  - Single Place: Info (`catalog-single-place-info.html`)
  - Single Place: Reviews (`catalog-single-place-reviews.html`)
- **Accounts**
  - Personal Info (`accounts-personal-info.html`)
  - Favorites (`accounts-favorites.html`)
  - Reviews (`accounts-reviews.html`)
  - Notifications (`accounts-notification.html`)
  - Sign In / Sign Up (modals on Home)
- **Vendor**
  - Add Business (`vendor-add-business.html`)
  - Business Promotion (`vendor-business-promotion.html`)
  - My Business (`vendor-my-business.html`)
- **Content**
  - Blog (`blog.html`)
  - Post (`post.html`)
  - About (`about.html`)
  - Help Center (`help-center.html`)
  - Contact (`contact.html`)
  - 404 (`404-not-found.html`)

## Getting started (local)

You can run it as a simple static site.

1. Install dependencies:

```bash
npm install
```

2. Compile SCSS (watch mode):

```bash
npm run sass
```

3. Open `index.html` in your browser (or use any local static server).

## Project structure

- `scss/` — source SCSS
- `dist/` — compiled CSS + plugin CSS
- `assets/` — images, icons, fonts
- `js/` — JavaScript and vendor scripts
- `*.html` — pages

## Credits

- UI/template implementation: **Shuvo Mallick**
- Inspired by Finder-style UI (design reference)

## License

This repository is provided as a template. If you plan to use it commercially, ensure that any third‑party assets (fonts, icons, plugins, images) are used in accordance with their respective licenses.
