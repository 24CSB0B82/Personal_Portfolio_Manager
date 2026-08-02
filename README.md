# Personal Portfolio Website

**Author:** Sai Jaswanth Vankadara  
**Roll Number:** 24CSB0B82  
**Department:** Computer Science and Engineering, National Institute of Technology, Warangal  
**Course:** CS1303 - Full Stack Development  

---

## 1. Design Rationale
The design of this personal portfolio website prioritizes clarity, clean aesthetics, and academic professionalism. Utilizing a cool white and slate color scheme (`#f4f6f9` background with `#2f6b5b` primary teal accents), the interface offers optimal visual contrast (complying with WCAG AA accessibility standards) without overwhelming the reader. Typography is structured hierarchically with a single `<h1>` title heading, followed by `<h2>` section headers, `<h3>` subsection titles, and clean body text.

## 2. Layout Technique Justification
The layout is implemented purely with **CSS Flexbox** and **CSS Grid** (with no external frameworks such as Bootstrap or Tailwind):
- **CSS Grid** is used for multi-column structured sections including the **Skills Grid**, **About Me Details**, and **Contact Section**. Grid allows items to align consistently across two dimensions while maintaining equal card heights.
- **Flexbox** is employed for one-dimensional layouts such as the **Sticky Header Navbar**, **Hero Card**, **Project Cards**, and **Footer Content**. Flexbox allows seamless alignment, spacing (`justify-content: space-between`), and directional shifting on mobile screens (`flex-direction: column`).

## 3. Responsive Breakpoints
Two media query breakpoints are implemented:
1. **Tablet View (`≤ 768px`)**: Transforms navigation into vertical stacked links, adjusts hero layout to a centered column, and stacks project cards vertically.
2. **Mobile View (`≤ 480px`)**: Reduces font scales, optimizes padding for small screens, and converts multi-column skill grids into a single-column layout.

## 4. Known Limitations
- The current contact form handles client-side input validation and submission feedback; server-side backend processing (Express/Node.js) and database persistence will be integrated in subsequent course assignments.
