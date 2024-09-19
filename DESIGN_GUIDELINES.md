# Design Guidelines for Resume Website

## 1. Color Scheme
- **Primary Color:** Sky Blue (#00D0FF) for headings (h1, h2, h3).
- **Secondary Color:** Light Gray (#F4F4F4) for header background.
- **Section Background:** Light Gray (#F0F0F0) for content sections.
- **Accent Color:** Light Blue (#B2C4FC) for footer.
- **Borders:** Light Gray (#DDD) for flexbox section borders.

## 2. Typography
- **Base Font:** Arial, sans-serif for body text.
- **Headings:** Sky Blue for h1, h2, h3 with sizes:  
  - h1: `2.5em`  
  - h2: `2em`  
  - h3: `1.5em`
- **Body Text:** Font size of `1em`, with line height `1.6`.

## 3. Layout & Positioning
- **Flexbox Layout:** Sections arranged side-by-side, wrapping on smaller screens. Flex-wrap allows sections to adapt to screen size.
- **Responsive Design:** Adjusted for:
  - **Tablet (max-width: 768px):** Sections grow to 45% width, heading sizes reduced.
  - **Mobile (max-width: 480px):** Sections stack vertically, font sizes adjusted for readability.

## 4. Media Queries
- **Tablet:** Two-column layout with smaller heading sizes.
- **Mobile:** Stacked layout with reduced font sizes.

## 5. Accessibility
- **ARIA Roles:** Implemented (`header`, `main`, `footer`) for better navigation.
- **Alt Text:** Included for profile image.
- **Color Contrast:** Ensured good contrast for readability across all elements.

