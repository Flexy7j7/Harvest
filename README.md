# LocalHarvest Boxes — Website Project

**Subject:** Web Development (WEDE5021)  
**Student:** Tshegofatso Maleka (ST10509340)  
**Group:** 1  
**Lecturer:** Charlotte Nukeri  
**Date:** August 2026

---

## Project Overview

Static multi-page website for **LocalHarvest Boxes**, a subscription-based farm-to-door produce delivery business based in Johannesburg, South Africa.

**Tagline:** *Fresh, local, and delivered weekly — no supermarket middlemen.*

### Pages

| File | Purpose |
|------|---------|
| `index.html` | Homepage — hero, how-it-works, featured farms, CTA |
| `about.html` | Story, mission/vision, farm partner profiles |
| `services.html` | Box sizes & pricing, sample contents table, add-ons |
| `enquiry.html` | Subscription enquiry form with client-side validation |
| `contact.html` | Contact details, contact form, Google Maps embed |

### Technologies

- HTML5
- CSS3 (external `css/style.css`) — Flexbox & CSS Grid, media queries
- Vanilla JavaScript (`js/main.js`) — mobile nav toggle + form validation
- Google Fonts: Playfair Display + Lato
- Hosting target: GitHub Pages
- Version control: Git / GitHub

---

## How to View Locally

1. Clone or download this repository.
2. Open `index.html` in a modern browser (Chrome / Firefox recommended).
3. Or serve with a simple local server:

```bash
# Python 3
python3 -m http.server 8000

# Then visit http://localhost:8000
```

---

## Part 2 — CSS Styling & Responsive Design

### Design System

| Token | Value |
|-------|-------|
| Primary green | `#3d6b4f` |
| Dark green | `#1e2f22` |
| Body text | `#2c3e2d` |
| Muted text | `#5a6b5c` |
| Background | `#faf9f6` |
| Alt background | `#f0efe9` |
| Heading font | Playfair Display |
| Body font | Lato |

### Layout Approach

- **Desktop (>900px):** Multi-column CSS Grid / Flexbox layouts
- **Tablet (≤900px):** 2-column grids where appropriate
- **Mobile (≤600px):** Single-column stacks, hamburger navigation

### Responsive Features Implemented

- [x] External single `style.css` linked from all 5 pages
- [x] CSS reset + base typography (rem units)
- [x] Sticky header with logo, nav, CTA button
- [x] Mobile hamburger menu (JS toggle + ARIA)
- [x] Flexbox / Grid for cards, forms, footer
- [x] Media queries at 900px and 600px breakpoints
- [x] `srcset` + `sizes` on key images for resolution switching
- [x] Hover / focus states and subtle box-shadows
- [x] Floating WhatsApp button
- [x] Client-side form validation with error messages
- [x] Google Maps embed on Contact page

### Screenshots

> **Note for submission:** Capture screenshots of the site at Desktop (≥1024px), Tablet (~768px) and Mobile (~375px) viewports and place them in an `images/screenshots/` folder. Reference them below.

```
images/screenshots/
  desktop-home.png
  tablet-home.png
  mobile-home.png
  desktop-services.png
  mobile-enquiry.png
```

*(Screenshots to be added after testing in Chrome DevTools device toolbar.)*

---

## Changelog

### 2026-08-07 — Part 2 Complete

- Created full 5-page static site structure
- Built external `css/style.css` with:
  - CSS reset, colour palette, typography scale
  - Flexbox & CSS Grid layouts
  - Hover, focus and active states
  - Media queries for tablet (900px) and mobile (600px)
- Added `srcset` / `sizes` attributes on farm and about images
- Implemented mobile navigation toggle in `js/main.js`
- Implemented client-side validation for Subscribe and Contact forms
- Added sticky header, WhatsApp float button, Google Maps embed
- Wrote this README with design notes and references

### Part 1 Feedback Corrections

*(If lecturer feedback was received on the proposal, log corrections here.)*

- No formal feedback document was provided at the time of Part 2 development.
- Proposal content (organisation overview, goals, features, timeline, budget) has been followed as the source of truth for page structure and copy.

---

## File Structure

```
localharvestboxes/
├── index.html
├── about.html
├── services.html
├── enquiry.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/          (optional local assets / screenshots)
└── README.md
```

---

## Git / GitHub Notes

Recommended commit history for Part 2:

1. `Initial project structure and HTML pages`
2. `Add base CSS reset, typography and colour system`
3. `Build desktop layouts with Grid and Flexbox`
4. `Add responsive breakpoints and mobile navigation`
5. `Implement form validation and interactive elements`
6. `Update README with Part 2 documentation and changelog`

Repository should be **private** as required by the brief.  
Deploy via **GitHub Pages** (Settings → Pages → Deploy from main branch / root).

---

## References

Afrihost, 2024. Domain Name Registration. [Online] Available at: https://www.afrihost.com/site/domains [Accessed 29 July 2026].

GitHub, 2024. GitHub Pages Documentation. [Online] Available at: https://docs.github.com/en/pages [Accessed 29 July 2026].

Google Fonts, 2024. Google Fonts Library. [Online] Available at: https://fonts.google.com [Accessed 7 August 2026].

Google Maps Platform, 2024. Embed a Map. [Online] Available at: https://developers.google.com/maps/documentation/embed [Accessed 29 July 2026].

MDN Web Docs, 2024. Client-side form validation. [Online] Available at: https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation [Accessed 7 August 2026].

MDN Web Docs, 2024. Responsive images. [Online] Available at: https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images [Accessed 7 August 2026].

Mozilla Foundation, 2024. MDN Web Docs – CSS Reference. [Online] Available at: https://developer.mozilla.org/en-US/docs/Web/CSS [Accessed 7 August 2026].

Pexels / Unsplash, 2024. Free Stock Photos for Commercial Use. [Online] Available at: https://www.pexels.com / https://unsplash.com [Accessed 29 July 2026].

W3Schools, 2024. HTML Forms and Validation. [Online] Available at: https://www.w3schools.com/html/html_forms.asp [Accessed 29 July 2026].

W3C, 2024. Web Content Accessibility Guidelines (WCAG) 2.1. [Online] Available at: https://www.w3.org/TR/WCAG21/ [Accessed 29 July 2026].

---

*Student Project — WEDE5021 | Not a live commercial site*
