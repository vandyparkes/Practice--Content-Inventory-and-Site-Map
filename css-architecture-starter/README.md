# CSS Architecture Starter

Use this small page for Module 2 practice if you do not want to use your capstone yet.

## Files

- `index.html`: sample content with repeated patterns.
- `styles.css`: CSS scaffold with layer sections and starter comments.

## Practice goal

Build a maintainable CSS system:

- layer order
- custom properties
- base styles
- layout/composition
- components
- utilities
- states
- print styles

Keep notes about what changed and why.

## Notes

Layer order is reset, base, layout, components, utilities, overrides. Later layers win, so exceptions stay out of component rules.

Three token decisions:
- One accent color for buttons, focus, and the current nav link.
- A 8 / 16 / 24 / 32 / 48 spacing scale instead of one-off padding values.
- One radius shared by buttons and cards.

CSS is easier to maintain at `--color-accent`: changing that one token updates the button, the focus outline, and the current-page link together.

