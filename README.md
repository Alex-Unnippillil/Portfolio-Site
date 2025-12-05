# Portfolio-Site

Personal portfolio website built with **HTML5** and **CSS3**.

## File structure

Portfolio-Site/
- `index.html` – Home
- `about.html` – About Me
- `projects.html` – Projects
- `contact.html` – Contact Me
- `css/base.css` – Shared styles and colour system
- `css/mobile.css` – Mobile layout (≤ 599px)
- `css/tablet.css` – Tablet layout (600–1023px)
- `css/laptop.css` – Laptop / desktop layout (≥ 1024px)
- `assets/alex.png` – used on About page + video poster
- `assets/intro.mp4` – 45–60s intro video

---

## Responsive viewport

The site uses fluid container (`width: 92%`–`88%`) so the layout grows and shrinks smoothly instead of using fixed pixel widths. Images and the video use `max-width: 100%` and will scale down on smaller screens.

CSS files loaded w/ media attributes

- **Mobile – `mobile.css` (≤ 599px)**  
  • Single‑column layout for the About and Projects sections.  
  • Cards and the contact form stretch to full width for readaibility on phones.

- **Tablet – `tablet.css` (600–1023px)**  
  • Uses simple floats to place the photo and the text next to eachother on the About page.  
  • Projects in two columns, header title is left‑aligned with navigation on the right.

- **Laptop/Desktop – `laptop.css` (≥ 1024px)**  
  • Widens the container slightly and keeps the two‑column Projects layout.  
  • Navigation spacing is adjusted for larger screens.

Only floats, inline‑block, and block‑level elements are used

---

## Gradients

1. **Standard linear gradient (Home page hero)**  
   - Selector: `.hero` in `base.css`.  
   - Uses `background-image: linear-gradient(to bottom, var(--grad-top), var(--grad-bottom));`  
   - a light vertical green gradient behind message on the **Home** page.

2. **Angled linear gradient (footer on all pages)**  
   - Selector: `footer` in `base.css`.  
   - Uses `background-image: linear-gradient(45deg, var(--grad-angle-1), var(--grad-angle-2));`  
   - 45° gradient is applied to the **footer** on every page

 gradient colours are defined once in `:root` as CSS custom properties (`--grad-top`, `--grad-bottom`, `--grad-angle-1`, `--grad-angle-2`) and then reused.

---

## Colour scheme 
palette is based on an ** green/teal scheme** .

**Neutral surfaces & text**

- `--bg: #f9fafb` – background.  
- `--surface: #ffffff` – header/footer panels.  
- `--ink: #111827` – nmain text.  
- `--muted: #6b7280` –  secondary text and dates.  
- `--border: #e5e7eb` – subtle borders 

**Brand / accent colours**

- `--brand: #68c015` – main colour(buttons, active navigation underline).  
- `--brand-dark: #2d850a` – for hover and stronger emphasis.  
- `--brand-soft: #28e08a` – used in gradients and highlights.  
- `--indigo-soft: #96dfe9` – used for small details.

**Gradient colours**

- `--grad-top: #effff6`  
- `--grad-bottom: #e2ffe0`  
- `--grad-angle-1: #a5fcb4`  
- `--grad-angle-2: #93fd9c`

This colour shceme were chosen so that:

- Text passes common contrast guidelines against the background, follows a clean design layout and it matches my video
---
