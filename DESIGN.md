---
name: Artisanal Hearth
colors:
  surface: '#fdf9f3'
  surface-dim: '#dddad4'
  surface-bright: '#fdf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ed'
  surface-container: '#f1ede7'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e6e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#4d444b'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0ea'
  outline: '#7e747c'
  outline-variant: '#cfc3cc'
  surface-tint: '#755377'
  primary: '#331736'
  on-primary: '#ffffff'
  primary-container: '#4a2c4d'
  on-primary-container: '#ba94bb'
  inverse-primary: '#e3b9e3'
  secondary: '#7d5700'
  on-secondary: '#ffffff'
  secondary-container: '#ffc55f'
  on-secondary-container: '#755100'
  tertiary: '#1b2500'
  on-tertiary: '#ffffff'
  tertiary-container: '#303b0f'
  on-tertiary-container: '#98a66f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd6fe'
  primary-fixed-dim: '#e3b9e3'
  on-primary-fixed: '#2c1030'
  on-primary-fixed-variant: '#5b3c5e'
  secondary-fixed: '#ffdeaa'
  secondary-fixed-dim: '#f5bd58'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5f4100'
  tertiary-fixed: '#dbe9ac'
  tertiary-fixed-dim: '#bfcd92'
  on-tertiary-fixed: '#161f00'
  on-tertiary-fixed-variant: '#404b1e'
  background: '#fdf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e6e2dc'
  fig-deep: '#4A2C4D'
  amber-warm: '#D9A441'
  paper-wash: '#FAF6F0'
  ink-black: '#221E1F'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  price-tag:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  container-padding-mobile: 20px
  container-padding-desktop: 40px
  gutter: 16px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 48px
  section-gap: 80px
---

## Brand & Style

The design system for this project is built on the narrative of an "Artisanal Hearth"—a space that is warm, grounded, and deeply human. The brand personality balances the sophistication of a specialty roastery with the unpretentious warmth of a neighborhood local. It speaks with a "dry-humored" yet "plainspoken" voice, avoiding the over-polished corporate veneer in favor of character and craft.

The visual style is **Minimalist with Tactile accents**. It leverages heavy white space (using the warm off-white background) and high-quality typography to convey quality. While the layout remains clean and functional for mobile-first utility, the interactions and visual details feel organic and intentional, mirroring the daily ritual of baking and roasting.

The emotional response should be one of "effortless comfort." It is a digital extension of the physical café: reliable, inviting, and devoid of clutter.

## Colors

The palette is driven by the organic tones of the café’s namesake. **Deep Fig Purple** serves as the primary brand anchor, used for headers, primary buttons, and critical UI elements to establish a sense of richness. **Warm Amber** is strictly an accent color; it is used sparingly for highlights, status indicators, or small decorative flourishes to draw the eye without overwhelming the content.

The **Warm Off-White** background creates a "paper-like" feel that is softer on the eyes than pure white, reinforcing the artisanal, printed-menu aesthetic. All body text uses **Near-Black** for maximum legibility and a classic "ink-on-paper" look. This high-contrast pairing ensures accessibility and a timeless quality.

## Typography

This system uses a classic pairing: **Playfair Display** for headlines and **Inter** for body text. 

The serif headlines provide "character"—they are slightly traditional but elegant, conveying the history of the old picture-framing shop and the craft of the roast. Headlines should use a tighter line height and slight negative letter spacing for a modern, editorial feel.

The sans-serif body text is chosen for its utilitarian clarity. It remains neutral and highly readable on mobile screens. We use `tabular-nums` for prices in the menu to ensure they align cleanly in lists. Labels and secondary navigation items use uppercase styling with increased letter spacing to create a distinct visual hierarchy from the narrative body copy.

## Layout & Spacing

This design system follows a **fluid grid philosophy** optimized for mobile-first delivery. On mobile, the layout is strictly a single-column stack with generous side margins (20px) to prevent content from feeling cramped.

On desktop, the layout expands to a 12-column grid with a maximum content width of 1100px to maintain the "neighborhood" feel rather than appearing like a sprawling corporate site. 

**Spacing Rhythm:**
- **Vertical Stacking:** Use the 8px-based system. Small gaps (8px) for labels and titles; medium gaps (24px) for paragraphs; large gaps (48px) between logical content blocks.
- **Section Breaks:** Significant vertical breathing room (80px+) is used between major sections (e.g., between the Hero and the "Reasons to Visit") to allow the photography and typography to "breathe."
- **Reflow:** Components like the Menu and Catering packages reflow from a 1-column stack (Mobile) to a 2-column or 3-column grid (Desktop) only when the line lengths would otherwise become too wide for comfortable reading.

## Elevation & Depth

This system avoids heavy shadows and synthetic depth in favor of **Tonal Layers**. 

Hierarchy is established through color blocks and low-contrast borders. The "paper-wash" background is the base. Elements that need to feel "closer" to the user, such as cards for catering packages or the Visit information table, use a subtle 1px border in a slightly darker shade of the background or the primary purple at a very low opacity (10%).

There are no heavy drop shadows. Where elevation is necessary (e.g., the primary call-to-action button), a soft, ambient "ink-tinted" shadow is used—extremely diffused and barely perceptible, mimicking the way a piece of heavy cardstock sits on a wooden table.

## Shapes

The shape language is **Soft (Level 1)**. 

Because the brand is grounded and traditional, sharp corners feel too aggressive, while pill-shapes feel too "tech-startup." A subtle 0.25rem (4px) corner radius on buttons, images, and cards provides a "human" touch that feels hand-finished rather than machine-cut. 

Interactive elements like buttons should feel sturdy. Use the same 4px radius consistently across all UI components to maintain a cohesive, structured look.

## Components

### Buttons
- **Primary Call to Action:** Filled Deep Fig Purple (#4A2C4D) with White text. Bold Inter typography. This is the only element that uses this visual weight on the page.
- **Secondary Links:** Text-only links in Ink Black (#221E1F) with a simple underline. They should feel "plainspoken" and avoid competing with the primary action.

### Menu Items
- Arranged in a vertical list. The item name is Playfair Display (Headline-MD), the price is Inter (Price-tag), and the description is Inter (Body-MD).
- Use small, Amber Warm (#D9A441) circular badges for dietary markers (V, VG, GF) placed next to the item name.

### Catering Cards
- Stacked vertically on mobile. A subtle 1px border (#4A2C4D at 10% opacity) defines the container. 
- The price should be the most prominent element after the package title, highlighted in Deep Fig Purple.

### Visit Table
- A simple, clean table for opening hours. 
- Alternating row backgrounds (zebra striping) using a slightly darker tint of the background color for high legibility. 
- No vertical borders; only horizontal lines to guide the eye across.

### Shopfront Image & Hero
- Full-bleed or edge-to-edge images on mobile. 
- Use a Deep Fig Purple overlay at 20-30% opacity on the Home Hero to ensure the white Playfair Display text remains legible over the photograph.