# Frontend Assignment – Figma Homepage Recreation

A take-home frontend implementation demonstrating visual fidelity and component architecture using Nuxt 3. This project recreates the IntelliToggle landing page from a provided Figma design, with verification using Pixelay overlay comparison.

## Live Demo

**Production URL:** [https://intellitoggle.onrender.com](https://intellitoggle.onrender.com)

## Tech Stack

- **Nuxt 3** (v3.21.0) – SSR/SSG framework
- **Vue 3** – Composition API with `<script setup>`
- **TailwindCSS** (v4.1.18) – Utility-first styling
- **Vite** – Build tooling

## Project Overview

This project focuses on:

1. **Visual fidelity** – Matching the Figma design as closely as possible
2. **Maintainable architecture** – Using modular, section-based components
3. **Responsive design** – Desktop and mobile breakpoints
4. **Verification** – Using Pixelay to validate layout accuracy

## Architecture Overview

```
components/
├── layout/
│   ├── Header.vue          # Global header with navigation
│   └── Footer.vue          # Global footer
└── sections/
    ├── Hero.vue            # Hero section
    ├── Logos.vue           # Logo strip
    ├── Intro.vue           # Introduction section
    ├── OpenFeature.vue     # OpenFeature integration info
    ├── Rollout.vue         # Rollout features
    ├── Comparison.vue      # Feature comparison
    ├── AI.vue              # AI delivery section
    ├── Pricing.vue         # Pricing table
    ├── Why.vue             # Why IntelliToggle section
    └── CTA.vue             # Call-to-action

layouts/
└── default.vue             # Base layout wrapper

pages/
└── index.vue               # Home page (composes sections)
```

### Why Section-Based Architecture?

Instead of building the entire page in a single component, I broke it into **10 discrete section components**. This approach:

- **Improves maintainability** – Each section can be modified independently
- **Enables reusability** – Sections could be reordered or reused across pages
- **Simplifies testing** – Sections are isolated units with clear boundaries
- **Keeps the page file clean** – `pages/index.vue` acts as a composition layer
- **Matches design structure** – Sections map directly to Figma frames

The `layouts/default.vue` wrapper handles persistent UI (header/footer), while page-level components focus purely on content composition.

## Key Implementation Decisions

### Component Architecture

- Used auto-imported components (`SectionsHero`, `LayoutHeader`) rather than explicit imports
- Kept section components stateless and presentational
- Extracted layout components (Header, Footer) for reuse across potential future pages

### Styling Approach

- Pure utility-first Tailwind classes – no custom CSS beyond base configuration
- Responsive modifiers (`sm:`, `md:`, `lg:`) for breakpoint-specific styling
- Configured custom colors in Tailwind config to match design system
- Used semantic class grouping for readability

### Configuration

- Minimal Nuxt config – only necessary for TailwindCSS Vite plugin and font preconnect
- No additional modules or plugins to keep the setup lightweight
- Leveraged Nuxt's defaults for routing and auto-imports

### Responsive Design

- Mobile-first utility classes with progressive enhancement
- Grid-based layouts that reflow naturally across breakpoints
- Tested at common breakpoints: 375px (mobile), 768px (tablet), 1440px (desktop)

### Accessibility Basics

- Semantic HTML (`<section>`, `<nav>`, `<footer>`)
- Alt text on images
- Focus states on interactive elements
- Proper heading hierarchy

## Pixelay Verification

Pixelay overlay comparison was performed to validate visual accuracy.

**Location:** `/pixelay/`

- `pixelay-desktop.png` – Desktop layout overlay
- `pixelay-mobile.png` – Mobile layout overlay
- `notes.md` – Comparison notes

### Summary

- Overall layout structure matches Figma design closely
- Minor differences exist due to font rendering and browser subpixel rounding
- Spacing and typography are consistent with design system
- Responsive behavior maintains visual hierarchy across breakpoints

## Setup Instructions

```bash
# Install dependencies
npm install

# Start development server (http://localhost:3000)
npm run dev

# Build for production
npm run build

# Preview production build locally
npm run preview
```

## Tradeoffs / If More Time

Given the 6–8 hour timebox, I prioritized visual fidelity and architecture over production polish. With additional time, I would:

1. **Image optimization** – Use `@nuxt/image` for responsive images and lazy loading
2. **Accessibility audit** – Full WCAG 2.1 AA pass with axe-devtools
3. **Lighthouse optimization** – Target 90+ scores across all metrics
4. **Animation polish** – Add scroll-triggered animations and micro-interactions
5. **CMS integration** – Demonstrate how sections could pull from a headless CMS
6. **Component tests** – Add Vitest unit tests for interactive components
7. **Storybook documentation** – Isolated component development environment

## Assignment Requirements Checklist

- ✅ Nuxt 3 + Vue 3 + TailwindCSS
- ✅ Responsive design (desktop + mobile)
- ✅ Interactive elements (navigation, buttons, hover states)
- ✅ Pixelay overlays captured (desktop + mobile)
- ✅ Clean, modular component architecture
- ✅ Deployed live demo
- ✅ Documentation complete

---

**Assignment completion time:** ~6 hours  
**Focus areas:** Visual fidelity, component structure, responsive design
