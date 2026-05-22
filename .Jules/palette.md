## 2026-05-22 - Adding aria-label to Placeholder-Only Inputs and Icon-Only Links
**Learning:** In templates where forms rely heavily on placeholders instead of explicit labels, and footers use icon-only anchor tags, screen readers lack context, reducing accessibility.
**Action:** Always verify that input fields without `<label>` elements, and links containing only icons (like social media links), have an appropriate `aria-label` attribute to ensure screen-reader compatibility.
