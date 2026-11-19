# NexusCore — Responsive Company Website

A clean, multi-page corporate website built with semantic HTML5, Tailwind CSS, and vanilla JavaScript. Designed to be fully responsive across mobile, tablet, and desktop breakpoints.

**Live Demo:** [https://responsive-company-website-wine.vercel.app](https://responsive-company-website-wine.vercel.app)

---

## Project Overview

NexusCore represents a modern IT consulting and enterprise solutions firm. The website provides visitors with an overview of the company's value proposition, leadership team, service offerings, and a validated contact channel.

### Key Features
* **Multi-Page Architecture:** Four dedicated pages (`Home`, `About`, `Services`, and `Contact`) with consistent branding and navigation.
* **Responsive Navigation:** Desktop horizontal navbar that collapses into an interactive mobile hamburger menu on smaller screens (`< 768px`).
* **Modern SaaS Card Styling:** Soft pastel-tinted feature and service cards with smooth hover elevation effects.
* **Client-Side Form Validation:** Real-time JavaScript validation on the Contact page checking for non-empty names, valid email formats, and minimum message lengths.
* **Consistent Footer:** Multi-column footer containing company info, quick navigation links, and contact details across all pages.

---

## Tech Stack

* **Markup:** HTML5 (Semantic tags: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
* **Styling:** Tailwind CSS (via CDN)
* **Icons:** Font Awesome 6
* **Interactivity:** Vanilla JavaScript (ES6+)
* **Deployment:** Vercel

---

## Folder Structure

```text
responsive-company-website/
├── index.html       # Home page (Hero section + Core features)
├── about.html       # About page (Company story + Leadership team)
├── services.html    # Services page (6-card service grid)
├── contact.html     # Contact page (Validated inquiry form)
├── script.js        # Mobile navigation toggle logic
├── office.jpg       # Corporate office image asset
└── README.md        # Project documentation
