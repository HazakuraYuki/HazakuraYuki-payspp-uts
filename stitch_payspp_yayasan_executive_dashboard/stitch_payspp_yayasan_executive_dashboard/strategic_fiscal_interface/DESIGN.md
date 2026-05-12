---
name: Strategic Fiscal Interface
colors:
  surface: '#f6fafb'
  surface-dim: '#d7dbdc'
  surface-bright: '#f6fafb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f5'
  surface-container: '#ebeeef'
  surface-container-high: '#e5e9ea'
  surface-container-highest: '#dfe3e4'
  on-surface: '#181c1d'
  on-surface-variant: '#3e494b'
  inverse-surface: '#2d3132'
  inverse-on-surface: '#eef1f2'
  outline: '#6e797b'
  outline-variant: '#bdc8cb'
  surface-tint: '#006876'
  primary: '#006572'
  on-primary: '#ffffff'
  primary-container: '#028090'
  on-primary-container: '#f6fdff'
  inverse-primary: '#77d4e5'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fc'
  on-secondary-container: '#57657a'
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
  secondary-fixed: '#d5e3fc'
  secondary-fixed-dim: '#b9c7df'
  on-secondary-fixed: '#0d1c2e'
  on-secondary-fixed-variant: '#3a485b'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb782'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#6f3801'
  background: '#f6fafb'
  on-background: '#181c1d'
  surface-variant: '#dfe3e4'
typography:
  display-lg:
    fontFamily: manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-lg:
    fontFamily: inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 28px
  body-md:
    fontFamily: inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  data-mono:
    fontFamily: inter
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
  unit: 4px
  container-max-width: 1440px
  gutter: 24px
  margin-desktop: 40px
  margin-mobile: 16px
  grid-columns: '12'
---

## Brand & Style

The design system is engineered for executive-level oversight within educational foundations. It prioritizes clarity, fiscal responsibility, and high-density data visualization without compromising on a premium aesthetic.

The visual style is **Corporate / Modern** with a curated **Glassmorphism** overlay. The interface utilizes a "layered intelligence" approach: a clean, minimalist base that uses semi-transparent surfaces to indicate hierarchy and focus. The overall atmosphere is analytical and sophisticated, designed to instill confidence in strategic decision-makers through precise alignments and a refined color palette.

## Colors

The palette is anchored by a deep **Executive Teal** (#028090), symbolizing stability and growth. 

- **Primary:** Used for main actions, active states, and brand identifiers.
- **Secondary:** Slate grays provide a professional, neutral foundation for text and UI architecture.
- **Surface & Background:** Soft whites and ultra-light grays (#F8FAFC) minimize eye strain during long analytical sessions.
- **Functional/Status:** High-fidelity colors with slightly desaturated tones to maintain an enterprise feel while ensuring immediate cognitive recognition of financial health markers.

## Typography

This design system utilizes a dual-font strategy to balance character with utility. 

**Manrope** is used for headlines and display metrics to provide a modern, refined geometric feel. **Inter** is the primary workhorse for body text and data tables, chosen for its exceptional legibility and neutral tone.

For financial data, always enable **tabular figures** (`tnum`) to ensure that columns of numbers align vertically, facilitating easier comparison of foundation balances and expenditures.

## Layout & Spacing

The system employs a **12-column fluid grid** for the primary dashboard, allowing for modular analytics widgets that can scale from 3 to 12 columns. 

- **Rhythm:** A 4px baseline grid ensures vertical consistency across all components.
- **Density:** High-density layouts are preferred for data-rich environments, using tight 24px gutters to maximize screen real estate.
- **Breakpoints:** 
  - **Desktop (1440px+):** Full 12-column visibility with persistent lateral navigation.
  - **Tablet (768px - 1439px):** Reflows to an 8-column grid; sidebar collapses to icons.
  - **Mobile (Under 768px):** Single column stack with a 16px safe area.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and **Glassmorphism**. 

- **Level 0 (Base):** Soft gray background (#F8FAFC).
- **Level 1 (Cards):** Pure white surfaces with a subtle 1px border (#E2E8F0) and a soft, diffused shadow (Y: 4px, Blur: 12px, Opacity: 4%).
- **Level 2 (Overlays/Modals):** Glassmorphic surfaces with a 12px backdrop blur and 80% opacity white fill. These are used for temporary filters or secondary analytical views.
- **Level 3 (Popovers):** Higher contrast shadows (Y: 8px, Blur: 24px, Opacity: 8%) to indicate immediate focus.

## Shapes

The shape language is consistently **Rounded**, striking a balance between the rigidity of traditional banking and the approachability of modern SaaS.

- **Standard Cards/Containers:** 12px corner radius.
- **Buttons/Inputs:** 8px corner radius for a precise, professional look.
- **Status Chips:** Full pill-shape (999px) to distinguish them from interactive buttons.
- **Data Visualizations:** Bar charts and progress indicators should use 4px rounded caps to maintain the visual theme.

## Components

### Buttons
- **Primary:** Solid Teal (#028090) with white text.
- **Secondary:** Ghost style with Slate Gray border and text.
- **States:** Hover states should utilize a subtle darken (5%), and active states a slight inner shadow for tactile feedback.

### Analytics Cards
The core of the system. Every card must include a title (Label Caps), a primary metric (Headline XL), and a trend indicator (Status Color). Glassmorphic accents are applied to the header section of charts to separate controls from data.

### Input Fields
Minimalist 1px borders (#CBD5E1). On focus, the border transitions to Primary Teal with a subtle 3px outer glow (Primary color at 10% opacity).

### Executive Icons
Use 24px grid icons with a consistent 1.5pt stroke weight. Avoid filled icons unless indicating an active state in the sidebar navigation.

### Data Tables
Zero-border horizontal rows. Use alternating "Zebra" stripes in ultra-light gray (#F1F5F9) only for tables exceeding 15 rows. Headers are sticky and use a semi-transparent glass effect to maintain context while scrolling.