---
name: PaySPP Design System
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
  secondary: '#5a5f60'
  on-secondary: '#ffffff'
  secondary-container: '#d9dedf'
  on-secondary-container: '#5c6263'
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
  secondary-fixed: '#dee3e4'
  secondary-fixed-dim: '#c2c7c8'
  on-secondary-fixed: '#171c1e'
  on-secondary-fixed-variant: '#424849'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb782'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#6f3801'
  background: '#f6fafb'
  on-background: '#181c1d'
  surface-variant: '#dfe3e4'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  caption:
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
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 40px
  margin-mobile: 16px
  stack-sm: 4px
  stack-md: 12px
  stack-lg: 24px
---

## Brand & Style

The design system is engineered to bridge the gap between high-end fintech reliability and the approachability required for an educational parent portal. The aesthetic is **Corporate Modern** with a infusion of **Glassmorphism** for depth. It targets parents and guardians in Indonesia, prioritizing clarity, financial transparency, and ease of use to reduce "payment anxiety."

The visual language communicates "Premium Utility" through:
- **Trustworthiness:** A stable Professional Teal foundation.
- **Transparency:** Clear data visualization and explicit status indicators.
- **Simplicity:** High-fidelity components that minimize cognitive load during financial transactions.
- **Modernity:** Subtle gradients and soft shadows that give the interface a tactile, high-end SaaS feel.

## Colors

The palette is anchored by **Professional Teal**, a color that evokes stability and growth. 

- **Primary:** Used for main actions, active states, and brand-heavy components like the sidebar background or primary buttons.
- **Secondary:** A very light tint of the primary teal used for subtle backgrounds and hover states to maintain a cohesive brand ecosystem.
- **Semantic/Status:** High-saturation colors optimized for legibility against white and light gray backgrounds. These are critical for the "Paid," "Pending," and "Overdue" statuses central to the tuition workflow.
- **Neutrals:** A cool-toned slate gray scale that keeps the interface feeling clean and professional, avoiding the muddiness of warmer grays.

## Typography

This design system utilizes a dual-font strategy to balance character with functionality:
- **Manrope** is used for headlines. Its geometric yet friendly curves provide a modern fintech feel and ensure the school portal feels "premium."
- **Hanken Grotesk** is used for body copy and UI labels. Its sharp, contemporary lines offer exceptional legibility for financial data and dense payment histories.

On mobile devices, `headline-xl` should scale down to `28px` and `headline-lg` to `24px` to maintain a balanced visual hierarchy on smaller screens.

## Layout & Spacing

The system employs a **12-column fluid grid** for desktop and a **4-column grid** for mobile. 

- **Sidebar:** A collapsible sidebar (280px expanded, 80px collapsed) sits on the left.
- **Top Nav:** A 72px high fixed navigation bar handles global search and profile management.
- **Spacing Rhythm:** Based on an 8px baseline. Use `stack-md` (12px) for spacing between elements within a card and `stack-lg` (24px) for spacing between major sections.
- **Responsive Behavior:** On mobile, margins reduce to 16px and cards stack vertically. The sidebar transforms into a bottom navigation bar or a slide-out drawer.

## Elevation & Depth

This design system uses a combination of **Ambient Shadows** and **Glassmorphism** to create a structured hierarchy.

- **Level 0 (Background):** Flat `#F9FAFB`.
- **Level 1 (Cards/Sidebar):** White surface with a soft, diffused shadow: `0px 4px 20px rgba(2, 128, 144, 0.05)`. Note the subtle primary color tint in the shadow to maintain brand warmth.
- **Level 2 (Modals/Dropdowns):** Elevated surfaces with a more pronounced shadow: `0px 10px 32px rgba(0, 0, 0, 0.1)`.
- **Glassmorphism:** Reserved for top navigation bars and card headers. Use a `backdrop-filter: blur(12px)` with a semi-transparent white fill (`rgba(255, 255, 255, 0.8)`) to create a sense of lightness and technical sophistication.

## Shapes

The shape language is **Rounded**, conveying safety and approachability.

- **Buttons & Inputs:** 0.5rem (8px) radius.
- **Standard Cards:** 1rem (16px) radius.
- **Feature/Hero Cards:** 1.5rem (24px) radius.
- **Status Pills:** Fully rounded (pill-shaped) to distinguish them from interactive buttons.

A subtle 1px border using `#E5E7EB` should be applied to all cards to ensure definition against the light gray background, even in low-contrast environments.

## Components

### Buttons
- **Primary:** Solid `#028090` with white text. High-emphasis.
- **Secondary:** Transparent with `#028090` border and text. 
- **Ghost:** No border, primary color text. Used for less frequent actions.

### Cards
- Standard cards feature a subtle top-to-bottom gradient (White to `#FDFDFD`). 
- Include a "Header Section" within cards using the Glassmorphism effect for important financial summaries.

### Input Fields
- Use floating labels. Active states should feature a 2px border in Professional Teal and a soft glow effect (inner shadow).

### Chips & Status Indicators
- **Paid:** Light green background with dark green text.
- **Pending:** Light orange background with dark orange text.
- Use a small dot icon inside the chip to improve accessibility for colorblind users.

### Sidebar
- Collapsible navigation with icons. The active state should be indicated by a vertical bar on the left and a subtle primary-tinted background behind the menu item.

### Data Tables
- Minimalist design with no vertical borders. Use zebra striping with the Secondary Color (`#F2F7F8`) for row hover states.