---
name: Foundation Admin
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
  on-surface-variant: '#3d4947'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#6d7a77'
  outline-variant: '#bcc9c6'
  surface-tint: '#006a61'
  primary: '#00685f'
  on-primary: '#ffffff'
  primary-container: '#008378'
  on-primary-container: '#f4fffc'
  inverse-primary: '#6bd8cb'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#595c5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#727577'
  on-tertiary-container: '#fbfdff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#89f5e7'
  primary-fixed-dim: '#6bd8cb'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#005049'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  h1:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  h2:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  h3:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
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
  container-padding: 24px
  card-gap: 20px
  section-margin: 32px
  input-padding: 12px
---

## Brand & Style
This design system is built for clarity, transparency, and administrative efficiency. The brand personality is grounded in academic professionalism, favoring functional minimalism over decorative flair. It aims to evoke a sense of organized calm, ensuring that school administrators can focus on data and reports without visual fatigue. 

The style utilizes a **Modern-Minimalist** approach. It avoids the heavy complexity of enterprise software by using ample whitespace and a restrained color palette. The visual language relies on structural alignment and clear information hierarchy, making it ideal for monitoring school funds, student progress, and foundation assets.

## Colors
The palette is centered around a primary Teal, chosen for its association with wisdom, growth, and stability. 

- **Primary Teal (#0D9488):** Used for primary actions, active navigation states, and brand accents.
- **Secondary Gray (#64748B):** Used for secondary text, icons, and supporting UI elements to provide contrast without competing with the primary color.
- **Surface & Background:** The background is kept exceptionally clean using a mix of pure white (#FFFFFF) for cards and a very light cool gray (#F8FAFC) for the canvas to differentiate layers subtly.
- **Status Colors:** Use a standard semantic set (Success: Green, Warning: Amber, Error: Rose) but desaturated to match the professional tone.

## Typography
This design system utilizes **Inter** for its exceptional legibility in data-heavy environments. The typeface is treated with a utilitarian approach.

- **Headlines:** Use Bold and Semi-Bold weights with slight negative letter spacing to create a cohesive, modern look for page titles and card headers.
- **Body Text:** Standardized at 14px for most dashboard content to maximize information density while maintaining readability. 
- **Labels:** Small caps or medium weights are used for table headers and form labels to create a clear distinction from user-generated data.

## Layout & Spacing
The layout follows a **Fixed-Fluid hybrid grid**. The sidebar navigation is fixed at 260px, while the main content area expands to fill the remaining width, capped at a maximum readability width for ultra-wide screens.

- **Grid:** A 12-column grid is used for the main content area.
- **Whitespace:** Use generous padding (24px) within cards and sections to ensure the UI feels "clean" and breathable.
- **Rhythm:** All margins and paddings are multiples of 8px to maintain a strict vertical and horizontal rhythm.

## Elevation & Depth
Depth is handled with a "Layered Flat" philosophy. We avoid heavy skeuomorphism in favor of subtle tonal separation.

- **Surface Tiers:** The main dashboard background is the lowest layer. Cards and containers sit one level above, separated by a very thin border (#E2E8F0).
- **Shadows:** Use a single, soft "Ambient Shadow" for elevated elements like cards and dropdowns. The shadow should be highly diffused: `0px 4px 12px rgba(0, 0, 0, 0.05)`.
- **Interactions:** On hover, cards may increase their shadow slightly or show a primary-colored border hint to indicate interactivity.

## Shapes
The shape language is "Soft-Professional." By using **Roundedness Level 2 (8px)**, we move away from the harshness of sharp corners common in legacy school software, without appearing too "bubbly" or consumer-focused.

- **Cards & Inputs:** 8px corner radius.
- **Buttons:** 8px corner radius to match.
- **Badges/Chips:** Use a fully pill-shaped radius (999px) to distinguish them from interactive buttons.

## Components
- **Buttons:** Primary buttons use the Teal fill with white text. Secondary buttons use a light gray ghost style or a simple border. Use 12px vertical and 20px horizontal padding.
- **Cards:** White background, 1px border (#E2E8F0), and 24px internal padding. Card titles should be H3 or Body-LG (Bold).
- **Tables:** Minimalist design with no vertical lines. Use thin horizontal dividers. Header background should be slightly tinted (#F8FAFC) to separate it from row data.
- **Input Fields:** Use a 1px border that turns Teal on focus. Labels sit clearly above the input field in the Label-SM style.
- **Monitoring Reports:** Use simple progress bars (Teal for progress, Light Gray for track) and large-digit "Stat Counters" for quick scanning of KPIs like "Total Students" or "Monthly Budget."
- **Badges:** Small, pill-shaped indicators for status (e.g., "Active," "Pending"). Use a low-opacity background tint of the status color with high-contrast text.