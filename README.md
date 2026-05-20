<div align="center">

# Portfolio

A **single-page personal portfolio** for **Prajwal BR**—static **HTML** and embedded **CSS**, plus **Font Awesome** icons. No build step: open `index.html` or host the `PORTFOLIO-PROJECT` folder on any static host.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?logo=fontawesome&logoColor=white)](https://fontawesome.com/)

</div>

---

## Table of contents

- [Overview](#overview)
- [Features](#features)
- [Project structure](#project-structure)
- [Sections](#sections)
- [Assets](#assets)
- [Run locally](#run-locally)
- [Deploy](#deploy)
- [Customization ideas](#customization-ideas)
- [Original README gallery](#original-readme-gallery)

---

## Overview

This repository holds a **classic static portfolio**: header with name, role, and profile-style image; **About Me**; **Projects** with three sample entries and imagery; **Skills** with icon-backed tech list; and a **Contact** section with a styled form. Styling is self-contained in `index.html` (no separate CSS file).

---

## Features

| | |
|---:|---|
| **Responsive-minded layout** | Centered sections, max-width content, card-like sections with shadow |
| **Visual hierarchy** | Dark header, light body, rounded corners |
| **Skills row** | Font Awesome brands for HTML, CSS, JavaScript, React, Node.js |
| **Imagery** | Local images under `PORTFOLIO-PROJECT/images/` |
| **Zero dependencies** | No npm, no framework—only CDN for Font Awesome |

---

## Project structure

```
Portfolio/
├── README.md
└── PORTFOLIO-PROJECT/
    ├── index.html          # Full page + embedded <style>
    └── images/
        ├── man-6206549_1280.jpg              # Header / profile visual
        ├── website-6692147_1280 (1).png    # Project 1
        ├── ai-generated-8261668_1280.jpg   # Project 2
        └── internet-1952019_1280.jpg        # Project 3
```

---

## Sections

1. **Header** — Name **PRAJWAL BR**, subtitle *Web Developer and Designer*, circular image.
2. **About Me** — Short professional introduction (HTML, CSS, JavaScript, React).
3. **Projects** — Three articles: portfolio site, e-commerce concept, login platform (each with image + blurb).
4. **Skills** — Unordered list with brand icons.
5. **Contact** — Intro copy + **Name**, **Email**, **Message** fields and **Send** button.

> **Note:** The contact `<form>` has no `action` or script—it is a **static UI demo**. To make it functional, wire it to a form backend (e.g. Formspree, Netlify Forms, or your own API).

---

## Assets

All project thumbnails and the header image live in **`PORTFOLIO-PROJECT/images/`**. Paths in HTML are relative (`images/...`), so keep that folder next to `index.html` when you move or deploy the site.

---

## Run locally

**Option A — open in browser**

- Navigate to `PORTFOLIO-PROJECT/` and double-click `index.html`, or drag the file into Chrome / Edge / Firefox.

**Option B — local server** (recommended so Font Awesome CDN behaves consistently)

```bash
cd PORTFOLIO-PROJECT
npx --yes serve .
# or: python -m http.server 8080
```

Then visit the URL the tool prints (e.g. `http://localhost:3000`).

---

## Deploy

Upload the **`PORTFOLIO-PROJECT`** directory (or its contents) to **GitHub Pages**, **Netlify**, **Cloudflare Pages**, **Vercel** (static), or any web host. Ensure **`images/`** stays beside **`index.html`**.

---

## Customization ideas

- Split embedded CSS into `styles.css` and link it for easier maintenance.
- Add `meta` description and Open Graph tags for social previews.
- Connect the contact form to a real endpoint or third-party form service.
- Replace placeholder copy and stock images with your own projects and screenshots.

---

## Original README gallery

The following lines are **preserved from the original README** (title, tagline, and all screenshots).

# Portfolio website

Portfolio website using only basic HTML and CSS 
![Screenshot 2024-09-17 234848](https://github.com/user-attachments/assets/ddbbd343-aacc-40f9-b2ff-f527f5d04df4)
![Screenshot 2024-09-17 234907](https://github.com/user-attachments/assets/5b431ff3-03da-4750-93c6-972d423c49f0)
![Screenshot 2024-09-17 234930](https://github.com/user-attachments/assets/12555f2b-3205-4ae9-87b8-37cd9247a1bf)
![Screenshot 2024-09-17 234942](https://github.com/user-attachments/assets/c5a7a17c-b722-4b6f-853b-9b93eef2df3c)
