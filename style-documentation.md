# MOBILE FIRST DESIGN

## Old / rare screen sizes

The base styles are designed for the iPhone 4 and iPhone 5 as the smallest mobile screens. The size is **320x480px** and **320x568px**, respectively.

The _Result Component_ occupies the first fullscreen followed by the _Summary Component_ for another fullscreen, and an _Attribution_ footer is at the bottom.

## Modern mobile devices

Standard Android devices can base on **360x640px**. The maximum width stops at around **480px**. The **768px** enters a tablet's screen width.

The design will occupy one fullscreen - no scrolls. All components are laid out on vertical arrangement.

## Font Readability

### Font sizes

**Body text**: set to **16px** to **18px** (or 1rem to 1.125rem). Never set body text below 14px to avoid requiring users to pinch-and-zoom.

**Headings (H1)**: **24px** to **32px** (or about 1.5em to 2em).

**Subheadings (H2, H3)**: **18px** to **24px** to maintain a structured information hierarchy.

**Buttons** and **Inputs**: At least **16px** so they are easy to tap without accidentally hitting adjacent links

For HTML **footers**, a font size between 14px and 16px (or 0.875rem to 1rem)

[read here](https://www.learnui.design/blog/mobile-desktop-website-font-size-guidelines.html)

### Spacings and Proportions

**Line Height**: Set line spacing between **1.5** and **1.8** times the font size (e.g., a 16px font should have a **24px** to **28px** line height).

**Line Length** (Measure): Keep line lengths to **50–75 characters** per line for optimal mobile readability.

[read here](https://medium.com/design-bootcamp/font-size-usage-in-ui-ux-design-web-mobile-tablet-52a9e17c16ce)

## Responsive HTML boxes

I used **container queries** to make box sizes responsive to screen devices, layout, viewport, etc.
