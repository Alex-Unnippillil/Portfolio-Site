# Portfolio-Site
Personal Portfolio Website using HTML-5 and CSS-3
Portfolio-Site/
    ├── index.html
    ├── about.html
    ├── projects.html
    ├── contact.html
    ├── css/
    │   ├── base.css

## Viewports
- **Mobile:** `mobile.css` for screens **≤ 599px**
- **Tablet:** `tablet.css` for **600–1023px**
- **Laptop/Desktop:** `laptop.css` for **≥ 1024px**

## Gradients
- **Linear gradient:** Applied on **Home page hero** section (`.hero`) using  
  `linear-gradient(to bottom, var(--grad-top), var(--grad-bottom))`.

- **Angled linear gradient:** Applied on **footer on all pages** using  
  `linear-gradient(45deg, var(--grad-angle-1), var(--grad-angle-2))`.


## Color Scheme 
  /* Neutral surfaces & text */
  --bg:#f9fafb;        /* page background */
  --surface:#ffffff;   /* cards, header */
  --ink:#111827;       /* main text */
  --muted:#6b7280;     /* secondary text */
  --border:#e5e7eb;    /* subtle borders */

  /* Brand colors */
  --brand:#68c015;     /* primary */
  --brand-dark:#2d850a;
  --brand-soft:#28e08a;
  --indigo-soft:#96dfe9; 