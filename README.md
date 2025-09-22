# Niyantri Cafe - Phase 2 Build

This repository contains the Phase 2 build for the Niyantri Cafe website (Rustic theme). It includes four production-ready HTML pages built with Tailwind CSS (via CDN), semantic HTML5 structure, and realistic content.

## File Structure
- index.html — Home page with a rustic hero, quick menu teaser, and highlights.
- about.html — Our Story section detailing cafe origins, sourcing, and community focus.
- menu.html — Menu page with three categories: Coffee, Tea, Pastries (10 items total) with descriptions and prices.
- contact.html — Contact page with cafe hours, location, map placeholder, and a working contact form (with basic validation).
- README.md — This file.

All images use the placeholder syntax: https://images.unsplash.com/photo-1525451031984-340d39c36aa8?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw0fHxkZXNjcmlwdGlvbnxlbnwwfDB8fHwxNzU4NDY0NDE1fDA&ixlib=rb-4.1.0&q=80&w=1080 to indicate where real visuals should be placed later. All images include descriptive alt attributes.

## Design & Implementation Notes
- Phase 2 uses Tailwind CSS utility classes exclusively (no custom CSS files).
- Pages are mobile-first and responsive, with a consistent rustic aesthetic.
- Navigation links between pages are internal for smooth user experience.
- All interactive elements implement basic focus and hover states, with transitions (transition-all duration-300).
- Accessibility considerations include semantic HTML, descriptive alt text, and keyboard accessibility for navigation.

## How to Run
- Since the site is static, simply open the HTML files in any modern browser:
  - index.html
  - about.html
  - menu.html
  - contact.html

No build tooling is required for this Phase 2. When you’re ready for Phase 3, we can add a build process, asset optimization, and deployment setup.

## Customization Tips
- Update text content directly in the HTML files.
- Replace https://images.unsplash.com/photo-1756758766177-b1213e59c1ae?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw4fHwuLi58ZW58MHwwfHx8MTc1ODQ2MjUwOHww&ixlib=rb-4.1.0&q=80&w=1080 placeholders with real image assets and ensure file paths are accessible.
- Adjust pricing or add new menu items by editing menu.html; follow the existing card structure for consistency.
