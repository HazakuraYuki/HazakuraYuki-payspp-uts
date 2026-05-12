---
name: Executive Educational Finance System
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#3e494b'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#6e797b'
  outline-variant: '#bdc8cb'
  surface-tint: '#006876'
  primary: '#006572'
  on-primary: '#ffffff'
  primary-container: '#028090'
  on-primary-container: '#f6fdff'
  inverse-primary: '#77d4e5'
  secondary: '#006b5f'
  on-secondary: '#ffffff'
  secondary-container: '#76f4e0'
  on-secondary-container: '#006f63'
  tertiary: '#894c16'
  on-tertiary: '#ffffff'
  tertiary-container: '#a7642d'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#9eefff'
  primary-fixed-dim: '#77d4e5'
  on-primary-fixed: '#001f24'
  on-primary-fixed-variant: '#004e59'
  secondary-fixed: '#79f7e3'
  secondary-fixed-dim: '#59dbc7'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005047'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb782'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#6f3801'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  h1:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  h2:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  h3:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
---

## Brand & Style

This design system is engineered for the precision and gravity required in school financial management. The brand personality is **authoritative, transparent, and efficient**, catering specifically to school administrators and financial officers who require high-density information presented with executive-level clarity.

The visual style is **Corporate Modern with subtle Glassmorphic accents**. It prioritizes a high-fidelity administrative feel, utilizing a structured grid to manage complex data while softening the experience through controlled roundedness and depth. The aesthetic balances the "seriousness" of financial auditing with the "approachability" of modern SaaS, ensuring that heavy data entry and reporting feel organized rather than overwhelming.

## Colors

The palette is anchored by a deep **Teal (#028090)**, conveying stability and professional growth. This primary tone is supported by a slate-based neutral scale to maintain high contrast and legibility in data-rich environments.

- **Primary (Teal):** Used for primary actions, active navigation states, and brand identifiers.
- **Secondary (Mint/Teal):** Used for accent elements and subtle highlights.
- **Status Colors:** These follow strict financial semantic rules.
    - **Green (Success/Paid):** For balanced ledgers and completed transactions.
    - **Orange (Warning/Pending):** For items awaiting approval or nearing deadlines.
    - **Red (Error/Overdue):** For late payments, budget deficits, or system errors.
    - **Blue (Info/Active):** For general system notices and non-critical active states.

## Typography

**Hanken Grotesk** is the exclusive typeface for this design system. It was selected for its contemporary geometry and exceptional legibility in numerical data.

- **Headlines:** Use Bold and SemiBold weights to establish clear information hierarchy.
- **Body:** Standardized at 16px for optimal readability. 14px is reserved for secondary metadata and high-density data tables.
- **Numbers/Monospace:** While the system uses Hanken Grotesk, tabular figures should be enabled via OpenType features to ensure financial columns align perfectly.

## Layout & Spacing

The design system utilizes a **12-column fluid grid** for desktop, transitioning to a **4-column grid for mobile**. The layout philosophy is centered on "Administrative Density," meaning information is packed efficiently without feeling cluttered.

- **Modular Spacing:** All spacing follows a 4px/8px base-unit system.
- **Executive Dashboard:** Uses a fixed-width container (max 1440px) centered in the viewport to maintain comfortable line lengths for financial reports.
- **Sidebars:** Persistent left-hand navigation (280px) provides quick access to core financial modules (Billing, Payroll, Audits).

## Elevation & Depth

Visual hierarchy is established through a combination of **soft ambient shadows** and **subtle glassmorphism**.

1.  **Level 0 (Background):** Neutral light gray (#F8FAFC) to differentiate from pure white cards.
2.  **Level 1 (Cards/Base):** Pure white surfaces with a soft 1px border (#E2E8F0) and an 8px corner radius.
3.  **Level 2 (Dropdowns/Modals):** Elevated with a medium diffusion shadow (Y: 4px, Blur: 12px, Opacity: 8% Black).
4.  **Glassmorphism:** Reserved for global headers and sidebars. Apply a `backdrop-filter: blur(12px)` with a semi-transparent white background (85% opacity) to create a sense of layering and "executive polish."

## Shapes

The design system uses a **Rounded (8px)** shape language. This specific radius is applied to cards, buttons, and input fields to soften the "industrial" feel of accounting software while maintaining a professional, structured edge.

- **Primary Radius:** 0.5rem (8px) for standard containers and inputs.
- **Large Radius:** 1rem (16px) for major dashboard widgets or "hero" containers.
- **Buttons:** Match the 8px radius for a cohesive, modern look.

## Components

### Buttons
- **Primary:** Solid Teal (#028090) with white text. High-contrast, 8px radius.
- **Secondary:** Transparent with a Teal border or subtle gray background for utility actions.
- **Tertiary/Ghost:** No border, Teal text. Used for "Cancel" or low-priority actions.

### Cards
- Standard 8px radius, white fill, 1px subtle border. 
- Use a 24px internal padding for financial summaries.
- Hover states include a slight increase in shadow depth and a teal-tinted border.

### Input Fields
- White background with a 1px border (#CBD5E1).
- Focus state: 1px Teal border with a soft teal outer glow (3px).
- Labels are always positioned above the field in `label-md` style for clarity.

### Data Tables (High Density)
- Alternating row stripes (Zebra striping) using #F8FAFC.
- Sticky headers with glassmorphic blur.
- Status chips (e.g., "Paid") use a light-tinted background of the status color with high-contrast text.

### Progress Indicators
- Financial targets or budget usage should use thin, rounded progress bars with the semantic status colors.