# Modern Responsive Personal Portfolio

A professional, high-performance personal portfolio website built by expanding a semantic HTML5 foundation with custom, modern responsive CSS styling, hosted live on **GitHub Pages**.

🔗 **Live Portfolio Site**: [https://asmit0125.github.io/personal-portfolio/](https://asmit0125.github.io/personal-portfolio/)  
📦 **GitHub Repository**: [https://github.com/Asmit0125/personal-portfolio](https://github.com/Asmit0125/personal-portfolio)

---

## Project Overview

This project builds upon a semantic HTML5 foundation, applying professional CSS architecture, modern responsive layout paradigms (CSS Grid & Flexbox), and a cohesive dark-mode design system. The site emphasizes **separation of concerns**—housing all layout, presentation, typography, and micro-interactions within an external stylesheet (`style.css`), with zero inline styles and strict semantic structure.

---

## Key Features & Required Components

### 1. Styling & Visual Design (CSS)
- **Cohesive Color Palette**:
  - Dark Slate Base: `#070a12`, `#0d1222`, with glassmorphic elevated surfaces (`rgba(18, 24, 43, 0.72)`).
  - Primary Accents: Deep Indigo (`#6366f1`), Electric Cyan (`#06b6d4`), and Vivid Purple (`#a855f7`).
  - High-contrast typography: Pure White (`#ffffff`), Slate (`#f8fafc`), and Muted Slate (`#94a3b8`).
- **Clean Typography**:
  - Web font: **Plus Jakarta Sans** (Google Fonts) with geometric sans-serif fallbacks.
  - Fluid type scaling using CSS `clamp()` for responsive headings and body text.
- **Modern Responsive Layouts**:
  - **Flexbox**: Sticky navigation header with glassmorphism, responsive alignment, and animated hover indicators.
  - **CSS Grid**: Multi-column responsive layout for Hero/About section, Technical Skills (`<dl>`), and Featured Projects (`<article>`).
- **Mobile-Friendly Media Queries**:
  - Breakpoints at `992px`, `768px`, and `480px` for seamless viewing across ultra-wide desktops, tablets, and smartphones.
- **Micro-Interactions**:
  - Subtle card lift (`transform: translateY(-6px)`), ambient glow effects, button hover transitions, and glowing status badge.

### 2. Architecture & Separation of Concerns
- **External Stylesheet**: All presentation styles reside strictly within `style.css`.
- **Zero Inline Styles**: Browser-default layouts and `style=""` attributes are eliminated.
- **Semantic HTML5 Preserved**: Fully preserves semantic landmarks: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<dl>`, `<dt>`, `<dd>`, `<form>`, and `<footer>`.
- **Accessibility (a11y)**:
  - Contrast-compliant color tokens.
  - Form controls with explicitly linked `<label>` tags.
  - Informative `alt` text for images.
  - Keyboard navigation with custom `:focus-visible` outline rings.
  - Media query `@media (prefers-reduced-motion: reduce)` support.

### 3. Deployment & Version Control
- **Git Version Control**: Clean commit history and branch management.
- **GitHub Pages**: Automatically deployed from the root directory of the `main` branch.
- **Domain**: Hosted on GitHub's global CDN at `asmit0125.github.io`.

---

## Directory Structure

```text
personal-portfolio/
│
├── index.html           # Semantic HTML5 document structure
├── style.css            # External stylesheet (tokens, grid, flexbox, media queries)
├── README.md            # Comprehensive project documentation
└── images/
    └── profile.jpg      # Optimized profile portrait asset
```

---

## Responsive Breakpoints Summary

| Breakpoint | Target Devices | Layout Adjustments |
|------------|----------------|---------------------|
| `> 992px`  | Desktop / Large Screens | 2-column Hero layout, multi-column Grid for Skills and Projects |
| `≤ 992px`  | Laptops / Large Tablets | Single-column Hero, centered profile card, adjusted section paddings |
| `≤ 768px`  | Portrait Tablets / Phablets | Vertical navigation flow, single-column project grid |
| `≤ 480px`  | Mobile Smartphones | Full-width buttons, compact padding, stacked contact details |

---

## Validation & Code Standards

- **HTML5**: Structured according to W3C living specifications with appropriate ARIA attributes.
- **CSS3**: Valid CSS with CSS Custom Properties (`:root`), standard Flexbox/Grid syntax, and cross-browser fallbacks.

---

## Author

**Asmit Prasad Sinha**  
Software Engineer & Open Source Contributor  
- **Email**: [kushwahaasmit88@gmail.com](mailto:kushwahaasmit88@gmail.com)  
- **GitHub**: [@Asmit0125](https://github.com/Asmit0125)  
- **Live Portfolio**: [https://asmit0125.github.io/personal-portfolio/](https://asmit0125.github.io/personal-portfolio/)
