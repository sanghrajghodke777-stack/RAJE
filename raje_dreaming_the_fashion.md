---
name: RAJE — Dreaming the Fashion
colors:
  surface: '#fdf9f5'
  surface-dim: '#ddd9d6'
  surface-bright: '#fdf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ef'
  surface-container: '#f1ede9'
  surface-container-high: '#ebe7e4'
  surface-container-highest: '#e6e2de'
  on-surface: '#1c1c19'
  on-surface-variant: '#504444'
  inverse-surface: '#31302e'
  inverse-on-surface: '#f4f0ec'
  outline: '#827474'
  outline-variant: '#d4c3c2'
  surface-tint: '#775656'
  primary: '#775656'
  on-primary: '#ffffff'
  primary-container: '#cfa7a7'
  on-primary-container: '#593c3c'
  inverse-primary: '#e6bcbc'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e5e2e1'
  on-secondary-container: '#656464'
  tertiary: '#625d5d'
  on-tertiary: '#ffffff'
  tertiary-container: '#b6afaf'
  on-tertiary-container: '#474243'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#e6bcbc'
  on-primary-fixed: '#2c1516'
  on-primary-fixed-variant: '#5d3f3f'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c9c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e8e1e1'
  tertiary-fixed-dim: '#ccc5c5'
  on-tertiary-fixed: '#1e1b1b'
  on-tertiary-fixed-variant: '#4a4646'
  background: '#fdf9f5'
  on-background: '#1c1c19'
  surface-variant: '#e6e2de'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '400'
    lineHeight: 80px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
    letterSpacing: -0.015em
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 26px
    fontWeight: '400'
    lineHeight: 34px
    letterSpacing: 0em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: 0em
  subheading:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0.005em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.14em
  price-editorial:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.04em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.02em
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

The design system embodies luxury editorial streetwear at the cross-section of Parisian haute couture and Tokyo underground minimalism. Targeted at discerning collectors, fashion enthusiasts, and style-forward youth, it communicates exclusivity, architectural balance, and avant-garde discipline.

The visual style embraces an **Editorial High-Contrast Minimalist** ethos:
- Vast plains of warm ivory canvas framing garments as museum pieces.
- Razor-sharp, unrounded geometry delivering an uncompromising, tailored silhouette.
- High-contrast, classic editorial typography juxtaposed against technical, utilitarian sans-serif accents.
- Subtle muted divisions, photographic bleeds, and tactile negative space that mimic heavyweight print lookbooks rather than standard digital storefronts.

## Colors

The palette is strictly restrained, balancing raw structure with delicate tactility:

- **Primary / Accent (`#CFA7A7`)**: Dusty Rose Pink. Used sparingly for curated accents, badge highlights, active micro-indicators, and editorial calls-to-attention.
- **Secondary / Primary Text (`#080808`)**: Deep Black. Provides supreme typographic contrast, solid buttons, structural rule lines, and grounding elements.
- **Tertiary / Soft Tint (`#F5EDED`)**: Soft Rose Tint. Applied to subtle image framing fills, toast alerts, selected size/swatch tiles, and technical spec backdrops.
- **Neutral / Canvas Ground (`#F8F4F0`)**: Warm Ivory. The foundational base surface mimicking archival cotton rag paper.
- **Surface Pure (`#FFFFFF`)**: Pure White. Dedicated to modal drawers, elevated product tiles, and floating cart containers.
- **Border Neutral (`#E6DFDA`)**: Muted Bone. Hairline divisions, layout scaffolding, and subtle structural separations.

## Typography

Typography functions as the primary visual architecture:

- **Playfair Display** provides high-fashion gravitas. Headlines should be rendered with editorial restraint—never overweighted or packed tightly.
- **Plus Jakarta Sans** introduces modernist geometry for commerce clarity, UI operations, sizing tables, and technical POD specifications.
- **Price Display**: Strictly formatted in Indian Rupee (`₹`), rendered in `price-editorial` using crisp letter spacing (e.g., `₹ 4,800`).
- **Editorial Sub-labels**: All collection badges, category stamps, and garment details use `label-caps` in strict uppercase format.

## Layout & Spacing

The layout is structured around an editorial 12-column grid system designed to simulate runway lookbook spreads:

- **Canvas Grid**: 12 columns on desktop (`>1024px`) with `1.5rem` gutters and generous `3.5rem` exterior margins.
- **Tablet Reflow** (`768px – 1024px`): 8 columns with `1.25rem` gutters and `2rem` margins.
- **Mobile Reflow** (`<768px`): 4 columns with `1rem` gutters and `1.25rem` margins. Product lists default to 1 or 2 asymmetric cards per row.
- **Vertical Cadence**: Generous section separation (up to `5rem` to `7rem` between runway chapters) balances high-density technical specs in the drawer and footer.

## Elevation & Depth

To sustain the runway lookbook aesthetic, heavy blurred dropshadows are forbidden. Depth is engineered purely through **architectural layering and hairline containment**:

- **Layer Tier 1 (Canvas)**: Warm Ivory (`#F8F4F0`) base canvas.
- **Layer Tier 2 (Panels & Cards)**: Crisp White (`#FFFFFF`) surfaces defined by 1px muted hairline borders (`#E6DFDA`).
- **Layer Tier 3 (Drawers & Flyouts)**: Minimalist slide-in cart drawers and fit matrices cast an ultra-subtle, ambient shadow (`0 20px 50px rgba(8, 8, 8, 0.05)`) with a translucent deep black backdrop blur (`rgba(8, 8, 8, 0.35)` with `8px` backdrop blur).
- **Interactive Planes**: Hover states invoke 1px hairline color transitions (from `#E6DFDA` to `#080808` or `#CFA7A7`) rather than vertical translation or shadow blooming.

## Shapes

The design system maintains strict **0px border-radius** across all UI elements (buttons, inputs, cards, image containers, drawer sheets, and chips). 

This sharp-edge geometry reinforces architectural tailor work, Japanese precision, and brutalist high fashion. Rounded corners are completely excluded.

## Components

### Buttons
- **Primary Action (Add to Bag / Pre-Order)**: Deep Black (`#080808`) background, Pure White (`#FFFFFF`) text, 0px radius, uppercase `label-caps` typography, `1rem` vertical padding. Hover shifts background to Dusty Rose (`#CFA7A7`) with text changing to Deep Black (`#080808`).
- **Secondary Action (View Lookbook / Specs)**: Transparent background, 1px Deep Black (`#080808`) outline, Deep Black text. Hover fills with Soft Rose Tint (`#F5EDED`).
- **Tertiary / Text Link**: Inline Deep Black with a permanent 1px bottom border spaced 4px below text.

### Product & Editorial Cards
- **Visual Presentation**: Strict rectangular photography bounding box (3:4 aspect ratio). Images render on warm ivory background tones.
- **Framing**: Hairline 1px border (`#E6DFDA`) on edge-to-edge lookbook grids. Hover triggers image scale transition (1.02x within masked bounds) without shifting layout geometry.
- **Pricing & Tags**: INR currency formatting (`₹ [amount]`) positioned in bottom-left metadata lockup with collection indicator.

### Input Fields & Selectors
- **Form Controls**: Hairline 1px borders (`#E6DFDA`), Warm Ivory (`#F8F4F0`) or White (`#FFFFFF`) interior, 0px radius.
- **Focus State**: Hairline transition to Deep Black (`#080808`) with zero glow/box-shadow.
- **Placeholder**: Monospace/clean sans muted text in `rgba(8, 8, 8, 0.4)`.

### Chips & Swatches (Sizes & Palette)
- **Size Chips (S, M, L, XL, XXL)**: Square 44x44px boxes, 1px border (`#E6DFDA`), Deep Black typography. Active state fills Deep Black (`#080808`) with Pure White (`#FFFFFF`) text.
- **Color Swatches**: Pure geometric 24x24px squares framed by a 1px border with a 3px interior margin gap when selected.

### Checkboxes & Radios
- **Checkboxes**: 18x18px square box, 1px border (`#080808`). Checked state fills Deep Black with an angular white hairline checkmark.
- **Radio Buttons**: 18x18px square box with a centered 8x8px inner square when selected (no circular forms).

### Slide-Out Cart Drawer & POD Specifications
- **Cart Drawer**: 420px wide desktop panel sliding from the right edge. Crisp white ground, border-left 1px (`#E6DFDA`). Contains micro-item lines, quantity step toggles, and direct ₹ checkout buttons.
- **Qikink POD Spec Module**: Technical accordion component highlighting fabric GSM (e.g., "280 GSM Heavyweight Terry Cotton"), print method (DTG/Screen), pre-shrunk treatment, and dispatch timeline. Rendered with clean tabular gridlines using `#E6DFDA` and `caption` typography.