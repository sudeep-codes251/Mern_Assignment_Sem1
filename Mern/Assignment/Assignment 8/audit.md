
# Responsive Audit — Leaf & Bean

## Viewport Tests

| Preview | Width | Expected Result |
|---|---|---|
| Desktop | 1200px | Navigation in one row; cards share available width. |
| Tablet | 768px | Spacing reduces and cards reflow. |
| Mobile | 375px | Navigation, cards, form and footer stack without overflow. |

## Issues Checked and Fixes

1. Navigation overflow at 375px:
   Header becomes a column and links wrap with gaps.

2. Images overflowing:
   Used max-width: 100% and height: auto.

3. Cards too narrow at tablet size:
   Flexible cards wrap at the 768px breakpoint.

4. Horizontal scrolling:
   Used box-sizing: border-box and fluid page width.

5. Buttons too small:
   Minimum 46px height and full-width buttons on mobile.

6. Text readability:
   16px body text on mobile and responsive heading sizes.

## Breakpoints

- @media (max-width: 768px) — Tablet adjustments.
- @media (max-width: 480px) — Mobile stacked layout.

## Testing in Chrome DevTools

1. Run index.html with Live Server.
2. Press F12.
3. Press Ctrl + Shift + M.
4. Test widths 1200px, 768px and 375px.
5. Check navigation, hero, cards, images and contact form.
6. Confirm there is no horizontal scrollbar.

## Screenshot Evidence

Save screenshots in a folder named screenshots:

- desktop-1200.png
- tablet-768.png
- mobile-375.png
