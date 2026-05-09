---
name: Lumina Academic Finance
colors:
  surface: '#f5faf8'
  surface-dim: '#d6dbd9'
  surface-bright: '#f5faf8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f5f2'
  surface-container: '#eaefed'
  surface-container-high: '#e4e9e7'
  surface-container-highest: '#dee4e1'
  on-surface: '#171d1c'
  on-surface-variant: '#3d4947'
  inverse-surface: '#2c3130'
  inverse-on-surface: '#edf2f0'
  outline: '#6d7a77'
  outline-variant: '#bcc9c6'
  surface-tint: '#006a61'
  primary: '#00685f'
  on-primary: '#ffffff'
  primary-container: '#008378'
  on-primary-container: '#f4fffc'
  inverse-primary: '#6bd8cb'
  secondary: '#545f73'
  on-secondary: '#ffffff'
  secondary-container: '#d5e0f8'
  on-secondary-container: '#586377'
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
  secondary-fixed: '#d8e3fb'
  secondary-fixed-dim: '#bcc7de'
  on-secondary-fixed: '#111c2d'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#ffdbce'
  tertiary-fixed-dim: '#ffb59a'
  on-tertiary-fixed: '#370e00'
  on-tertiary-fixed-variant: '#773215'
  background: '#f5faf8'
  on-background: '#171d1c'
  surface-variant: '#dee4e1'
typography:
  display-lg:
    fontFamily: Lexend
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Lexend
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  title-sm:
    fontFamily: Lexend
    fontSize: 18px
    fontWeight: '600'
    lineHeight: '1.4'
  body-base:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Lexend
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Lexend
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

This design system is built upon the principles of **Modern Minimalism** tailored for the educational sector. The primary objective is to demystify school commerce and provide a frictionless, "student-level" experience that feels both approachable and authoritative. 

The aesthetic is characterized by high legibility, generous whitespace, and a reduction of visual noise. By stripping away complex gradients and heavy shadows, the focus remains entirely on the financial data and the actions required by the student or parent. The tone is educational; the interface doesn't just process payments—it guides the user through their financial obligations with clarity and calm.

## Colors

The palette utilizes **Teal** as the primary driver for action, symbolizing growth and clarity. **Dark Blue** is reserved for headers and structural elements to provide a sense of institutional stability and professional grounding.

- **Primary (Teal):** Used for primary buttons, active states, and critical progress indicators.
- **Secondary (Dark Blue):** Used for navigation backgrounds, headings, and high-level information architecture.
- **Neutral (Grays/White):** A scale of cool grays is used for borders and subtle background shifts to separate content without relying on shadows.

## Typography

This design system uses **Lexend** exclusively. Specifically designed to reduce visual stress and improve reading proficiency, Lexend is the ideal choice for an educational payment platform. 

The type scale is generous to ensure accessibility across all age groups. Headlines are set with tighter tracking and heavier weights to provide clear landmarks, while body copy maintains a relaxed line-height for maximum readability during long-form billing reviews.

## Layout & Spacing

The design system employs a **Fixed Grid** model for desktop environments, centering content within a 1200px container to prevent eye strain on ultra-wide monitors. A 12-column grid with 24px gutters provides the structural foundation.

Spacing follows an 8px rhythmic scale. Components are grouped using "proximity as logic"—related information (like a tuition fee and its due date) uses `sm` spacing, while distinct sections are separated by `lg` or `xl` margins to create a clear visual hierarchy.

## Elevation & Depth

To maintain a "clean and simple" aesthetic, this design system rejects heavy, multi-layered shadows. Instead, it utilizes **Low-contrast outlines** and **Tonal layers**.

- **Surface Levels:** The main background is pure white. Secondary content or card backgrounds use a very light gray (`#F8FAFC`).
- **Borders:** Instead of shadows, use 1px solid borders in a light neutral tone to define element boundaries.
- **Active State:** Only the "active" or "hovered" card may use a very subtle, diffused ambient shadow (0px 4px 12px rgba(0,0,0,0.03)) to indicate interactivity.

## Shapes

The shape language is defined by **Rounded** corners. A base radius of 0.5rem (8px) is applied to buttons, input fields, and small cards. This creates a friendly, approachable atmosphere that softens the "coldness" often associated with financial software. 

Larger containers and primary dashboard cards use a 1rem (16px) radius to emphasize their role as distinct content vessels.

## Components

### Navigation
- **Desktop:** A top navigation bar with a Dark Blue background. Links are white with a Teal underline for the active state.
- **Mobile:** A fixed bottom navigation bar utilizing high-contrast icons and labels for thumb-friendly access.

### Cards
Cards are flat with a 1px border. They should avoid internal complexity. Header areas within cards use the light muted surface color to distinguish between metadata and the primary content.

### Tables
Tables must be "clean"—meaning no vertical lines. Horizontal lines should be thin and light gray. The header row should use the Dark Blue secondary color for text to ensure high contrast against the white table body.

### Inputs & Buttons
- **Inputs:** Use a soft gray border that turns Teal on focus. Labels always sit above the input field for accessibility.
- **Buttons:** Primary buttons are solid Teal with white text. Secondary buttons are outlined in Dark Blue.

### Educational Tooltips
Small info-icons (Teal) should be placed next to financial jargon. When clicked/hovered, they reveal a simple, plain-English explanation of the term.