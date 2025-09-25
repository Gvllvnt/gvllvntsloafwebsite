# Gvllvnt's Loaf Bakery Website

## Student Information
- **Name:** Thamanda Sobekwa
- **Student Number:** ST10460780
- **Course:** WEDE5020

## Project Overview
This project involves designing and developing a website for Gvllvnt's Loaf Bakery, an innovative Johannesburg-based bakery known for its South African flavour fusions. The goal is to create a bold online presence that drives enquiries and tells the brand's unique story.

## Website Goals and Objectives
- Showcase unique, flavour-forward products.
- Streamline the custom order and catering enquiry process.
- Highlight the brand's journey from Soweto to Maboneng.
- Drive social media engagement and community growth.

## Key Features and Functionality
- 5-Page Website (Home, About, Products, Enquiry, Contact)
- Responsive Design for all devices
- Contact and Enquiry Forms

## Timeline and Milestones
- Week 1: Project Planning & Content Sourcing (Complete)
- Week 2: HTML Structure & Basic Styling (Current Week)
- Week 3: Advanced CSS Styling & Responsive Design
- Week 4: JavaScript Implementation, Final Testing, and Launch

## Sitemap
Home (index.html)
│
├── About Us (about.html)
├── Our Products (products.html)
├── Custom Orders (enquiry.html)
└── Contact (contact.html)

## Changelog
All notable changes to this project are documented in this section.

- **[2025-08-17]**
  - **Added:** Initial project structure and repository setup.
  - **Added:** Basic HTML structure for all five core pages (`index.html`, `about.html`, `products.html`, `enquiry.html`, `contact.html`).
  - **Added:** Placeholder images in the `/images` directory.
  - **Added:** Initial version of the `README.md` documentation.

- **[2025-08-20]**
  - **Added:** Complete CSS styling in `css/style.css` for all pages.
  - **Updated:** Formspree form endpoints added to `enquiry.html` and `contact.html` for functional form handling.
  - **Fixed:** Corrected file paths for images and stylesheets to resolve broken links.## Part 2: Enhanced CSS Styling & Responsive Design

### Implementation Overview
This phase focused on transforming the static website into a fully responsive web application using mobile-first design principles, advanced CSS techniques, and responsive image optimization.

### Technical Features Implemented

#### CSS Architecture
- **Approach:** Mobile-first responsive design
- **Methodology:** CSS Custom Properties (Variables) for maintainability
- **Layout Systems:** CSS Grid for product layouts, Flexbox for navigation
- **Typography:** Modular scale using REM units for accessibility

#### Responsive Breakpoints
1. **Mobile First (< 768px):** Single-column layout, stacked navigation
2. **Tablet (768px - 1023px):** 2-column product grid, horizontal navigation
3. **Desktop (≥ 1024px):** 3-column product grid, optimized spacing
4. **Large Desktop (≥ 1200px):** Max-width container, enhanced typography

#### Advanced CSS Features
- CSS Grid for complex layouts
- Flexbox for component alignment
- CSS Custom Properties for consistent theming
- Advanced pseudo-classes (:hover, :focus, :active)
- CSS transitions for smooth interactions
- Accessibility support (prefers-reduced-motion)
- Print styles for usability

#### Responsive Images
- **Primary Method:** CSS `max-width: 100%` with `height: auto`
- **Advanced Demonstration:** `srcset` attribute implementation on hero image
- **Optimization:** Responsive image techniques for performance

### Responsive Testing Evidence

The website was thoroughly tested across multiple devices and screen sizes to ensure optimal user experience.

#### Desktop View (> 1024px)
- Horizontal navigation menu with hover effects
- 3-column product grid layout using CSS Grid
- Optimized typography scale for large screens
- Enhanced spacing and layout proportions

#### Tablet View (768px)
![Tablet View](Media/tabletview.jpg)
- Adapted horizontal navigation for tablet interaction
- 2-column product grid layout
- Adjusted typography scale for medium screens
- Optimized touch targets for tablet use

#### Mobile View (375px)
![Mobile View](Media/mobileview.jpg)
- Vertical stacked navigation for touch devices
- Single-column layout for easy mobile scrolling
- Large touch targets (minimum 44px) for accessibility
- Optimized font sizes for mobile readability
- No horizontal scrolling detected across all pages

### Performance Optimizations
- **CSS:** Minimal, efficient selectors and reduced redundancy
- **Images:** Responsive loading with appropriate sizing
- **Layout:** Efficient rendering with CSS Grid and Flexbox
- **Accessibility:** Semantic HTML with proper ARIA labels

### Browser Compatibility
Tested and verified working on:
- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)

## Changelog

### Part 2 Implementation (2024-01-15)
- **Enhanced CSS Architecture:** Implemented mobile-first responsive design with CSS custom properties
- **Advanced Layout Systems:** Added CSS Grid for product layouts and enhanced Flexbox navigation
- **Responsive Breakpoints:** Established 768px (tablet) and 1024px (desktop) breakpoints
- **Typography Scale:** Implemented 8-point modular scale using REM units
- **Navigation Optimization:** Improved mobile navigation with better touch targets and text wrapping prevention
- **Interactive Elements:** Enhanced :hover, :focus states with smooth CSS transitions
- **Accessibility Features:** Added reduced motion support and print styles
- **Testing & Validation:** Comprehensive cross-browser and cross-device testing



## References

### Part 2 References
1. **MDN Web Docs** (2023). *CSS Grid Layout*. Mozilla Developer Network. Retrieved from [https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)

2. **MDN Web Docs** (2023). *Responsive Design*. Mozilla Developer Network. Retrieved from [https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

3. **Google Developers** (2023). *Responsive Web Design Basics*. Google Web Fundamentals. Retrieved from [https://developers.google.com/web/fundamentals/design-and-ux/responsive](https://developers.google.com/web/fundamentals/design-and-ux/responsive)

4. **W3C** (2023). *CSS Flexible Box Layout Module Level 1*. W3C Specification. Retrieved from [https://www.w3.org/TR/css-flexbox-1/](https://www.w3.org/TR/css-flexbox-1/)

5. **Web Accessibility Initiative** (2023). *WCAG 2.1 Accessibility Guidelines*. W3C. Retrieved from [https://www.w3.org/WAI/standards-guidelines/wcag/](https://www.w3.org/WAI/standards-guidelines/wcag/)

### Part 1 References (Maintained)
6. **ColorHexa** (2023). *Color Palettes*. Retrieved from [https://www.colorhexa.com/](https://www.colorhexa.com/)
7. **Google Fonts** (2023). *Poppins and Open Sans*. Retrieved from [https://fonts.google.com/](https://fonts.google.com/)
8. **Unsplash** (2023). *Free Image Library*. Retrieved from [https://unsplash.com/](https://unsplash.com/)
9. **Formspree** (2023). *Form Handling*. Retrieved from [https://formspree.io/](https://formspree.io/)