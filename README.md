# Accessibility Conformance Lab

Module 5 practice project focused on identifying, remediating, and testing web accessibility issues.

## Files

- `index.html`: Accessible page structure and content.
- `styles.css`: Responsive styles, focus indicators, contrast, and motion preferences.
- `workshop.svg`: Decorative workshop illustration.

## Practice Objectives

- Landmarks and heading structure
- Link and button names
- Keyboard access and visible focus
- Zoom and reflow
- Color contrast
- Form labels and required states
- Table captions and headers
- Image alternatives
- Reduced-motion preferences

## Accessibility Remediation

| Issue                                               | Fix                                                                | Retest Result                                               |
| --------------------------------------------------- | ------------------------------------------------------------------ | ----------------------------------------------------------- |
| Incorrect heading hierarchy                         | Replaced the hero subtitle heading with a paragraph.               | Heading hierarchy verified.                                 |
| Generic link names and empty button                 | Added descriptive accessible link names and button text.           | Accessible names verified.                                  |
| Missing focus indicators and skip link              | Added visible focus styles and a skip-to-main-content link.        | Keyboard navigation and skip link work as intended.         |
| Fixed-width layouts                                 | Added responsive widths, grid columns, and a media query.          | Passed at 200% zoom and narrow, medium, and wide viewports. |
| Insufficient contrast                               | Adjusted link colors, input borders, and focus indicators.         | Contrast improvements verified.                             |
| Missing form label associations and required states | Associated labels with inputs and corrected required attributes.   | Form labels and validation verified.                        |
| Missing table caption and headers                   | Added a caption and semantic table headers.                        | Table structure verified.                                   |
| Inappropriate image alternatives                    | Used empty alt attributes for decorative SVGs.                     | Decorative images excluded from the accessibility tree.     |
| Continuous animation                                | Limited animation to 4.8 seconds and added reduced-motion support. | Motion preferences verified.                                |

## Testing Results

- Lighthouse accessibility score: 100/100.
- W3C Nu HTML Checker: Passed.
- W3C CSS Validation Service: Passed.
- Browser accessibility-tree inspection: Semantic structure, accessible names, and control states verified.
- Manual keyboard, responsive layout, and reduced-motion tests passed.

## AI Disclosure

I used ChatGPT to suggest accessibility improvements and organize findings. I performed all tests and verified the fixes myself.
