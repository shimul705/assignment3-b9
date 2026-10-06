# 🏒 Hockey's — Hockey Club Landing Page

A responsive landing page for a professional hockey club, with training programs, club gear, FAQs and a contact form. Built with **Tailwind CSS** and **DaisyUI**.

> **Programming Hero — Level 1 · Assignment 3 (Batch 9)**
> Completed: **January 24, 2024**  
> Mark: **60 / 60** 🏆

<p>
  <a href="https://shimul705.github.io/assignment3-b9/"><img alt="Live Demo" src="https://img.shields.io/badge/Live-Demo-FF4240?style=for-the-badge&logo=githubpages&logoColor=white"></a>
  <a href="https://github.com/shimul705/assignment3-b9"><img alt="Source Code" src="https://img.shields.io/badge/Source-Code-131318?style=for-the-badge&logo=github&logoColor=white"></a>
  <img alt="Mark 60/60" src="https://img.shields.io/badge/Mark-60%2F60-2EA44F?style=for-the-badge">
</p>

---

## 🔗 Links

| | |
|---|---|
| **Live Site** | [shimul705.github.io/assignment3-b9](https://shimul705.github.io/assignment3-b9/) |
| **Repository** | [github.com/shimul705/assignment3-b9](https://github.com/shimul705/assignment3-b9) |

---

## 📌 Overview

**Hockey's** is my third Programming Hero assignment and my **first project with a CSS framework**.

Assignments 1 and 2 were written in hand-made CSS with my own media queries. This one is built almost entirely with **Tailwind CSS utility classes** and ready-made **DaisyUI components**. Those components include the navbar dropdown, carousel, radial progress, cards, rating, accordion and form inputs.

Responsive design is now done inline with Tailwind's `sm:` / `md:` / `lg:` / `xl:` prefixes instead of separate `@media` blocks. Several sections use **CSS Grid** with `col-span` / `row-span`.

---

## ✨ Page Sections

1. **Navbar:** the logo, the navigation links, a **Get Ticket** button, and a DaisyUI dropdown (hamburger) menu on mobile and tablet.
2. **Hero Slider:** a two-slide DaisyUI **carousel** with prev/next buttons, plus a dark "Meet all the heroes from the field" banner that overlaps the slide on desktop.
3. **Professional Hockeys Club:** four **radial progress** stats (Prayer Facility, Experienced Coach, Senior Player, Training Ground).
4. **Program Sections:** a grid of program cards with background images, a dark overlay and **Register Now!** buttons. The last card spans the full width.
5. **Our New Products:** six product cards with a rating, views, likes, price and free delivery, two per row on large screens.
6. **Clients Question:** an image beside a six-item DaisyUI **accordion** FAQ.
7. **Get In Touch:** phone, email and location cards beside a contact form (name, email, subject, phone, message), then a social media bar.
8. **Footer:** a contact block plus Company, Support and Services link columns.

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic structure (`header`, `nav`, `main`, `section`, `footer`) and form inputs |
| **Tailwind CSS** (CDN) | Utility classes, a custom colour config (`p-colour`, `subh-text`), Flexbox, Grid, responsive prefixes |
| **DaisyUI 4** | Navbar, dropdown, carousel, radial progress, card, rating, collapse/accordion, form controls |
| **Font Awesome** | Eye, heart, truck, envelope, phone and social icons |
| **Google Fonts** | `Manrope` (400–800) |
| **GitHub Pages** | Deployment |

---

## 📱 Responsive Design

| Breakpoint | Device | Layout |
|---|---|---|
| `≥ 1024px` (`lg`) | Desktop | Full nav links, the banner overlaps the slider, four stats in a row, two program cards + one wide card, FAQ image beside the accordion, contact cards beside the form |
| `≥ 1280px` (`xl`) | Large desktop | Product cards two per row |
| `768–1023px` (`md`) | Tablet | Hamburger menu, stats in a 2×2 grid, side-by-side image and text in product cards, a two-column contact form |
| `< 768px` | Mobile | A single column throughout, product images on top, stacked form fields, a centred footer |

---

## 📂 Project Structure

```
assignment3-b9/
├── index.html           # Page markup with Tailwind + DaisyUI classes
├── tailwind.config.js   # Tailwind config file
└── Images/              # Slider, program, product, FAQ and contact icons
```

---

## 🚀 Run Locally

```bash
git clone https://github.com/shimul705/assignment3-b9.git
cd assignment3-b9
```

Then open `index.html` in any browser. No build step is required: Tailwind, DaisyUI and Font Awesome load from CDNs, so an internet connection is needed.

---

## 📚 What I Learned

- Setting up **Tailwind CSS** and **DaisyUI** through a CDN and extending the theme with **custom colours**.
- Building layouts from **utility classes** instead of writing my own CSS file.
- Making the page responsive with **breakpoint prefixes** (`sm:`, `md:`, `lg:`, `xl:`) instead of `@media` blocks.
- Using ready-made **DaisyUI components** (carousel, radial progress, rating, accordion, dropdown) and customising them with utilities.
- Building **Grid** layouts with `grid-cols`, `col-span` and `row-span`.
- Pinning a **DaisyUI theme** (`data-theme="light"`) so the design doesn't switch to dark when the visitor's device is in dark mode.

---

## 👤 Author

**Shimul**
GitHub: [@shimul705](https://github.com/shimul705)

---

<sub>Part of my Programming Hero learning journey. Each assignment shows a step in my growth as a web developer.</sub>
