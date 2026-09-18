# Cape Bloom Bakery – Part 2: Designing the Visuals

## Student Details
- Student Name: Themba Macheke
- Student Number: ST10535158
- GitHub Username: ST10535158
- Organisation: Cape Bloom Bakery

## Part 2 Scope
Part 2 builds directly on Part 1 and focuses on:
1. External CSS styling.
2. Appropriate CSS selectors.
3. Desktop layout using Grid and Flexbox.
4. Typography and visual styling.
5. Hover, focus and active interaction states.
6. Responsive tablet and mobile layouts.
7. Relative units and responsive images.
8. Browser developer-tool testing.
9. README, changelog and GitHub version control.

## Website Pages
- index.html – Home
- about.html – About
- products.html – Products
- enquiry.html – Enquiry
- contact.html – Contact

## CSS Implementation
The five pages are linked to `css/style.css`. The stylesheet uses:
- Element, class and pseudo-class selectors.
- `rem`, `em`, `%`, `clamp()` and viewport-aware values.
- CSS Grid for product/content layouts.
- Flexbox for header and button alignment.
- Media queries at 800px and 560px.
- Typography properties including font-family, font-size, font-weight, line-height and letter-spacing.
- Colours, backgrounds, borders and box shadows.
- `:hover`, `:focus-visible` and active navigation styling.

## Responsive Design
### Desktop
Multi-column cards, two-column content areas and a multi-column footer are displayed.

### Tablet
At 800px and below, layouts reduce to fewer columns and major two-column sections stack.

### Mobile
At 560px and below, cards become single-column, navigation becomes a compact grid and buttons become full width.

## Responsive Image Evidence
The project folder includes the `images` directory for image assets. Where image assets are added, responsive images should use `srcset` and `sizes`, or a `<picture>` element, for example:

```html
<picture>
  <source media="(max-width: 560px)" srcset="images/product-small.jpg">
  <source media="(max-width: 800px)" srcset="images/product-medium.jpg">
  <img src="images/product-large.jpg"
       srcset="images/product-small.jpg 560w,
               images/product-medium.jpg 800w,
               images/product-large.jpg 1200w"
       sizes="(max-width: 560px) 94vw,
              (max-width: 800px) 92vw,
              1120px"
       alt="Cape Bloom Bakery product">
</picture>
```

## Testing Evidence – REQUIRED BEFORE FINAL SUBMISSION
Insert actual screenshots into this README showing:
1. Desktop view – wide browser/device.
2. Tablet view – approximately 800px.
3. Mobile view – approximately 560px or a mobile device.
4. Browser developer tools showing responsive/device testing.

Recommended screenshot captions:
- Figure 1: Desktop homepage.
- Figure 2: Tablet homepage.
- Figure 3: Mobile homepage.
- Figure 4: Developer Tools responsive testing.

Do not claim these screenshots were captured until the actual screenshots have been added.

## Browser Testing
Test the website in a modern browser. Check:
- Navigation on every page.
- Form controls.
- Text readability.
- Responsive layout.
- Button and link states.
- Keyboard focus.
- Images and assets.
- Console errors.

## GitHub
GitHub Username: ST10535158

Repository link:
[PASTE YOUR ACTUAL GITHUB REPOSITORY LINK HERE]

Suggested descriptive commits:
- Initial Part 1 HTML structure
- Updated content after Part 1 feedback
- Added external CSS stylesheet
- Added desktop Grid and Flexbox layouts
- Added typography and visual styles
- Added hover and focus states
- Added responsive tablet styles
- Added responsive mobile styles
- Added JavaScript enquiry interaction
- Updated README and changelog

## Changelog
### Part 1 Feedback Edits
- Standardised organisation as Cape Bloom Bakery.
- Standardised five-page navigation.
- Removed the previous CV-style Skills and Education page structure.
- Aligned website content with the Part 1 proposal.
- Organised HTML, CSS, JavaScript and image folders.

### Part 2
- Added external CSS stylesheet.
- Added reusable selectors.
- Added typography scale and spacing.
- Added CSS Grid and Flexbox.
- Added visual styling.
- Added hover/focus/active states.
- Added tablet and mobile breakpoints.
- Added relative sizing and responsive layout rules.
- Added client-side enquiry form feedback.
- Updated README for Part 2.
- Added testing and screenshot evidence requirements.

## References
- MDN Web Docs. (n.d.). HTML: HyperText Markup Language. https://developer.mozilla.org/en-US/docs/Web/HTML
- MDN Web Docs. (n.d.). CSS: Cascading Style Sheets. https://developer.mozilla.org/en-US/docs/Web/CSS
- MDN Web Docs. (n.d.). CSS Grid Layout. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout
- MDN Web Docs. (n.d.). CSS Flexible Box Layout. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout
- MDN Web Docs. (n.d.). CSS media queries. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries
- MDN Web Docs. (n.d.). Responsive images. https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images
- MDN Web Docs. (n.d.). JavaScript Guide. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide
- W3C Web Accessibility Initiative. (n.d.). Web Accessibility Initiative. https://www.w3.org/WAI/
