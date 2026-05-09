---
name: Institutional Precision
colors:
  surface: '#f6faf9'
  surface-dim: '#d7dbda'
  surface-bright: '#f6faf9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f4f3'
  surface-container: '#ebefee'
  surface-container-high: '#e5e9e8'
  surface-container-highest: '#dfe3e2'
  on-surface: '#181c1c'
  on-surface-variant: '#3e4949'
  inverse-surface: '#2c3131'
  inverse-on-surface: '#edf2f1'
  outline: '#6e7979'
  outline-variant: '#bdc9c8'
  surface-tint: '#006a6a'
  primary: '#006565'
  on-primary: '#ffffff'
  primary-container: '#008080'
  on-primary-container: '#e3fffe'
  inverse-primary: '#76d6d5'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#8b4823'
  on-tertiary: '#ffffff'
  tertiary-container: '#a96039'
  on-tertiary-container: '#fff9f7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#93f2f2'
  primary-fixed-dim: '#76d6d5'
  on-primary-fixed: '#002020'
  on-primary-fixed-variant: '#004f4f'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#ffb692'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#733512'
  background: '#f6faf9'
  on-background: '#181c1c'
  surface-variant: '#dfe3e2'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
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
  container-max: 1440px
  gutter: 24px
---

## Brand & Style
This design system is built for administrative clarity and institutional trust. It targets school leadership—specifically Principals and Financial Officers—who require immediate, legible access to financial health data without the distraction of decorative elements. 

The aesthetic follows a **Minimalist Corporate** approach. It prioritizes high legibility and a logical hierarchy of information. By removing complex shadows, gradients, and vibrant accent colors, the system creates an environment of "Institutional Calm," where the data itself is the primary interface. The visual language is authoritative yet accessible, mirroring the formal nature of academic management.

## Colors
The palette is intentionally restricted to maintain a formal, academic tone. 
- **Primary Teal (#008080):** Used for primary actions, active navigation states, and brand identification. It represents stability and professional focus.
- **Secondary White (#FFFFFF):** The primary surface color for cards and containers to maximize contrast and focus.
- **Neutral Grays:** A refined scale of grays handles everything else. Borders use a light gray to define boundaries without creating heavy visual weight, while text ranges from near-black for headings to medium-gray for metadata.
- **Background:** A very soft off-white (#F9FAFB) is used for the page canvas to provide subtle separation between the dashboard background and the white cards.

## Typography
Inter is used exclusively for its systematic, utilitarian character. It provides the neutral clarity required for a data-heavy payment dashboard. 
- **Hierarchy:** We use font weight rather than size alone to create hierarchy. Headings are semi-bold to establish clear sectioning.
- **Data Tables:** Numerical data should utilize tabular lining (mono-spaced numbers) where possible to ensure columns of figures align perfectly for easy comparison by the Principal.
- **Micro-copy:** Labels for status tags and table headers use a slightly smaller, medium-weight font to distinguish them from interactive data.

## Layout & Spacing
The layout follows a **Fixed Grid** model to ensure a consistent administrative experience across desktop monitors. 
- **Grid:** A 12-column grid system with a 24px gutter. 
- **Rhythm:** An 8px baseline grid dictates the vertical rhythm.
- **Structure:** The interface is built on a "Top-Down" hierarchy. The primary navigation sits at the very top, followed by a page header/breadcrumb area, and finally the content area. White space is used generously to group related payment metrics and prevent "information overwhelm."

## Elevation & Depth
In accordance with the minimalist brief, this design system avoids traditional enterprise shadows. Depth is communicated through **Low-contrast Outlines** and **Tonal Layering**:
- **Surface Tier 1:** The page background (#F9FAFB) represents the lowest level.
- **Surface Tier 2:** White cards (#FFFFFF) are placed on top of the background, defined by a 1px solid border (#E5E7EB).
- **Interactive States:** Subtle shifts in border color (e.g., from #E5E7EB to #D1D5DB) indicate hover states for interactive cards, rather than using drop shadows.
- **Focus:** Primary action buttons use solid color fills to create "functional depth" without needing physical metaphors.

## Shapes
The shape language is conservative and geometric. 
- **Corner Radius:** A "Soft" (4px) radius is applied to buttons, cards, and input fields. This provides a professional, modern feel that is less aggressive than sharp corners but more formal than highly rounded or pill-shaped designs.
- **Consistency:** All containers, from small chips to large data cards, must share the same base corner radius to maintain a unified institutional look.

## Components
- **Top Navigation Bar:** A clean, white bar with a 1px bottom border. Navigation links use Inter Label-MD. The active state is indicated by a Primary Teal bottom border (2px) or a change in text weight.
- **Simple Cards:** Containers for high-level metrics (e.g., "Total Fees Collected"). These have a 1px border (#E5E7EB), no shadow, and 24px internal padding.
- **Data Tables:** The core of the dashboard.
    - Headers: Light gray background (#F3F4F6) with uppercase Label-SM text.
    - Rows: 1px bottom border only; no zebra striping to keep the UI "light."
    - Cell Padding: 16px vertical padding for high readability.
- **Buttons:** 
    - Primary: Solid Teal (#008080) with White text.
    - Secondary: White background with a 1px Gray border and Teal or Gray text.
- **Input Fields:** Flat styling with 1px borders. Focus states use a Primary Teal border.
- **Status Chips:** Used for payment status (e.g., "Paid," "Pending"). Use a light gray background with dark gray text for a neutral, formal look, avoiding bright "stoplight" colors unless critical.