---
name: Academic Utility
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#3d4947'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#6d7a77'
  outline-variant: '#bcc9c6'
  surface-tint: '#006a61'
  primary: '#00685f'
  on-primary: '#ffffff'
  primary-container: '#008378'
  on-primary-container: '#f4fffc'
  inverse-primary: '#6bd8cb'
  secondary: '#5a5f62'
  on-secondary: '#ffffff'
  secondary-container: '#dce0e4'
  on-secondary-container: '#5e6367'
  tertiary: '#924628'
  on-tertiary: '#ffffff'
  tertiary-container: '#b05e3d'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#89f5e7'
  primary-fixed-dim: '#6bd8cb'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#005049'
  secondary-fixed: '#dfe3e7'
  secondary-fixed-dim: '#c3c7cb'
  on-secondary-fixed: '#171c1f'
  on-secondary-fixed-variant: '#43474b'
  tertiary-fixed: '#ffdbce'
  tertiary-fixed-dim: '#ffb59a'
  on-tertiary-fixed: '#370e00'
  on-tertiary-fixed-variant: '#773215'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  h1:
    fontFamily: Public Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  h2:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  h3:
    fontFamily: Public Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-sm:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 48px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style
This design system is built on the principles of **clarity, reliability, and accessibility**. Designed for a university student environment, the brand personality is helpful and straightforward, removing the friction often associated with financial transactions. 

The aesthetic follows a **Minimalist-Professional** direction. It avoids the aggressive polish of modern fintech startups and the rigid density of legacy banking software. Instead, it utilizes ample whitespace, a calming teal-based palette, and clear structural hierarchy to ensure students can navigate their payments without cognitive overhead. The emotional response should be one of "quiet competence"—a tool that works exactly as expected without unnecessary flourish.

## Colors
The palette is intentionally restrained to maintain focus on transactional data. 

- **Primary (Teal):** Used for call-to-action buttons, active states, and critical navigational highlights. It provides a sense of growth and stability.
- **Background (White):** The primary canvas. Use pure white to maximize contrast and maintain a clean, "paper-like" feel.
- **Neutral (Light Gray / Slate):** Used for secondary text, borders, and subtle backgrounds.
- **Functional Colors:** Use a standard red (#DC2626) for errors/overdue alerts and green (#16A34A) for successful payment confirmations.

## Typography
**Public Sans** is the sole typeface for this design system. It was chosen for its institutional heritage and exceptional readability in both digital and print contexts.

- **Headlines:** Use Bold or Semi-Bold weights with slight negative letter-spacing to create a strong visual anchor for page titles.
- **Body Text:** Use the Regular weight for all reading tasks. Ensure line heights are generous (1.5x) to prevent fatigue when viewing long tables of data.
- **Labels:** Use Medium or Semi-Bold weights for form labels and table headers to distinguish them from user-entered data.

## Layout & Spacing
This design system utilizes a **Fixed Grid** model for desktop views to ensure content remains readable and centered, transitioning to a fluid model for mobile.

- **Grid:** A 12-column system with 24px gutters.
- **Rhythm:** All spacing (padding, margins) must be increments of the 4px base unit. 
- **Sectioning:** Use 48px (xl) spacing between major page sections and 24px (md) between cards or related content groups. 
- **Alignment:** Content should generally be left-aligned to mimic the natural reading pattern of academic documents.

## Elevation & Depth
In alignment with the professional and clean aesthetic, depth is communicated through **Low-Contrast Outlines** and subtle tonal shifts rather than heavy shadows.

- **Surface Levels:** The background is white. Cards and containers use a 1px solid border (#E2E8F0).
- **Interactive Depth:** On hover, a card may transition from a light gray border to a primary teal border, or gain an extremely soft, diffuse shadow (0px 4px 12px rgba(0,0,0,0.05)).
- **Separation:** Horizontal rules (HR) should be used sparingly, relying on spacing and background color shifts (#F1F5F9) to define different functional areas.

## Shapes
The shape language is **Soft**, utilizing a consistent 4px (0.25rem) corner radius for most UI elements. This provides a modern touch while maintaining the structured, professional feel of an educational platform.

- **Standard Elements:** Buttons, input fields, and small cards use the 4px radius.
- **Large Containers:** Main content areas or modal windows may use a 8px (0.5rem) radius for a slightly softer appearance.
- **Icons:** Use linear, 2px stroke icons to match the weight of the typography and borders.

## Components
- **Buttons:** Solid Teal with white text for primary actions. Outlined Teal for secondary actions. Avoid purely decorative gradients.
- **Cards:** White background, 1px light gray border, 24px internal padding. Use for grouping student details, payment summaries, or semester overviews.
- **Tables:** No vertical borders. Use 1px horizontal dividers between rows. Table headers should have a light gray background (#F8FAFC) and bold labels.
- **Input Fields:** 1px border with a 4px radius. On focus, the border changes to Primary Teal with a 2px outer glow in a semi-transparent teal.
- **Navigation:** Simple top-bar or left-rail with clear text links. Use a bottom-border on the active link in the primary teal color.
- **Status Chips:** Small, pill-shaped indicators for "Paid," "Pending," or "Overdue." Use low-saturation background tints with high-saturation text for readability.