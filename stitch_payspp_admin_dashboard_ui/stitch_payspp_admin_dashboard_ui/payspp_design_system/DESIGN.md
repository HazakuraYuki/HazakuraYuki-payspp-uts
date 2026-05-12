---
name: PaySPP Design System
colors:
  surface: '#fbf8ff'
  surface-dim: '#dbd9e1'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f2fa'
  surface-container: '#efedf4'
  surface-container-high: '#e9e7ef'
  surface-container-highest: '#e4e1e9'
  on-surface: '#1b1b21'
  on-surface-variant: '#454651'
  inverse-surface: '#303036'
  inverse-on-surface: '#f2eff7'
  outline: '#767682'
  outline-variant: '#c6c5d3'
  surface-tint: '#4b57aa'
  primary: '#142175'
  on-primary: '#ffffff'
  primary-container: '#2e3a8c'
  on-primary-container: '#9ea9ff'
  inverse-primary: '#bcc3ff'
  secondary: '#0058bc'
  on-secondary: '#ffffff'
  secondary-container: '#0070eb'
  on-secondary-container: '#fefcff'
  tertiary: '#4b2000'
  on-tertiary: '#ffffff'
  tertiary-container: '#6d3200'
  on-tertiary-container: '#f09b63'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dfe0ff'
  primary-fixed-dim: '#bcc3ff'
  on-primary-fixed: '#000d60'
  on-primary-fixed-variant: '#333f91'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a41'
  on-secondary-fixed-variant: '#004493'
  tertiary-fixed: '#ffdbc7'
  tertiary-fixed-dim: '#ffb689'
  on-tertiary-fixed: '#311300'
  on-tertiary-fixed-variant: '#723603'
  background: '#fbf8ff'
  on-background: '#1b1b21'
  surface-variant: '#e4e1e9'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  title-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
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
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  data-mono:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
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
  container-max: 1440px
  gutter: 24px
---

## Brand & Style
The design system is engineered for the high-stakes environment of educational finance. It balances the rigor of enterprise software with the slick, user-centric interface of modern fintech platforms. The visual language conveys institutional stability while maintaining a modern, approachable edge that reduces the cognitive load of complex billing cycles.

Key characteristics include:
- **Operational Efficiency:** Dense but legible layouts optimized for rapid data processing and status monitoring.
- **Premium Trust:** A refined aesthetic using subtle glassmorphism and soft shadows to elevate the platform above utilitarian legacy software.
- **Clarity of Action:** High-contrast status indicators that guide the user toward urgent tasks (overdue payments, pending approvals) without causing alarm.

## Colors
The palette is anchored by **Deep Indigo** for core navigation and primary actions, symbolizing authority and security. **Professional Blue** is utilized for interactive elements and highlights, providing a familiar fintech feel.

**Slate Grays** form the backbone of the typographic hierarchy, ensuring high legibility against white surfaces. Status colors follow global semantic standards but are slightly desaturated to maintain a sophisticated professional tone, only gaining vibrance when user attention is strictly required. Use subtle background tints (5-10% opacity) of status colors for banners and row highlights.

## Typography
This design system utilizes **Hanken Grotesk** for high-level headings to provide a modern, sharp personality. **Inter** is the workhorse for all body copy and data-heavy views, chosen for its exceptional legibility and neutral tone.

For financial tables and tuition amounts, always enable **tabular numerals** (`tnum`) to ensure columns of numbers align vertically for easier scanning. Use `label-caps` for table headers and section overviews to create a clear structural distinction from interactive data.

## Layout & Spacing
The layout follows a **12-column fluid grid** for the main content area, with a fixed sidebar for primary navigation (280px). 

- **Desktop (1440px+):** 24px margins, 24px gutters.
- **Tablet (768px-1024px):** 16px margins, 16px gutters. Sidebar collapses to icon-only state.
- **Mobile (<768px):** 16px margins, fluid single-column layout. 

Spacing follows a strict 4px/8px baseline grid. Content-heavy dashboards should prioritize `md` (16px) spacing for internal card padding to maximize information density without appearing cluttered.

## Elevation & Depth
This design system uses a layered approach to depth, moving away from flat design toward a more tactile, "premium" feel:

1.  **Level 0 (Background):** Slate-50 (#F8FAFC) - The canvas.
2.  **Level 1 (Cards/Surface):** White (#FFFFFF) - Used for primary content. Features a 1px border (#E2E8F0) and a soft, diffused shadow: `0 4px 6px -1px rgb(0 0 0 / 0.05)`.
3.  **Level 2 (Modals/Overlays):** White - Elevated with a deeper shadow to focus attention: `0 20px 25px -5px rgb(0 0 0 / 0.1)`.
4.  **Glassmorphism Accents:** Applied to global headers and sidebars using a backdrop filter (`blur(12px)`) and a 70% opaque white background. This creates a sense of spatial awareness and depth in complex workflows.

## Shapes
The shape language is consistently rounded to humanize the financial experience. 
- **Small Components:** Buttons, inputs, and tags use `rounded-md` (8px).
- **Medium Components:** Content cards and containers use `rounded-lg` (12px-16px).
- **Interactive States:** Focus states should follow the container's radius with a 2px offset ring.
- **Icons:** Use a 1.5pt stroke weight with slightly rounded joins (0.5px-1px) to match the UI's geometry.

## Components
- **Buttons:** Primary buttons use the Deep Indigo gradient with a subtle 1px inner light border on the top edge. Secondary buttons are ghost-style with a slate border.
- **Status Chips:** Small, pill-shaped indicators. Use a light background tint of the status color with high-contrast text for maximum accessibility (e.g., Light Green BG with Dark Green Text).
- **Data Tables:** Clean, row-based layouts. Use 1px slate-200 dividers. Hover states should trigger a subtle light blue background shift (#F1F5F9).
- **Financial Cards:** Specifically designed for tuition balances. Use the glassmorphism effect for the "Total Balance" card at the top of dashboards to differentiate it from standard data cards.
- **Inputs:** High-contrast borders on focus (Professional Blue) with a soft glow shadow. Labels should always be visible (never placeholder-only).
- **Icons:** Minimalist line icons (24px grid). Avoid filled icons unless used for active navigation states.