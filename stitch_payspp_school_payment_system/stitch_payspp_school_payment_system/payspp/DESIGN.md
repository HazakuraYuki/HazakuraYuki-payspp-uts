---
name: PaySPP
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
  secondary: '#5c5f60'
  on-secondary: '#ffffff'
  secondary-container: '#dee0e2'
  on-secondary-container: '#606365'
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
  secondary-fixed: '#e1e2e4'
  secondary-fixed-dim: '#c5c6c8'
  on-secondary-fixed: '#191c1e'
  on-secondary-fixed-variant: '#444749'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb782'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#6f3801'
  background: '#f6fafb'
  on-background: '#181c1d'
  surface-variant: '#dfe3e4'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
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
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
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
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  container-max-width: 1200px
  mobile-margin: 16px
  desktop-gutter: 24px
---

## Brand & Style
The design system is built on the narrative of "Digital Trust for Education." It bridges the gap between traditional school administration and modern Indonesian fintech convenience. The visual style follows a **Corporate / Modern** aesthetic, heavily influenced by the streamlined user experiences of Indonesian "Super Apps."

The target audience consists of parents (primary users) and school administrators. To accommodate varying levels of digital literacy, the UI prioritizes clarity, large touch targets, and a realistic "layered" depth that feels familiar and dependable. The emotional response is one of security and efficiency—reducing the anxiety often associated with tuition deadlines and financial management.

## Colors
This design system utilizes a high-contrast primary palette focused on Teal to evoke professionalism and calm. 

- **Primary Teal (#028090):** Used for primary actions, active navigation states, and branding elements.
- **Background White (#FFFFFF):** The standard canvas for all views to maintain a clean, high-end feel.
- **Secondary Light Gray (#F3F4F6):** Employed for "container" backgrounds, section dividers, and subtle groupings to prevent visual fatigue.
- **Semantic Accents:** Standard Green (Paid/Success), Amber (Pending), and Red (Overdue) are used sparingly to communicate payment status clearly to parents at a glance.

## Typography
The system uses **Inter** exclusively to achieve a functional, utilitarian look that remains highly legible across different screen resolutions.

The typographic scale is designed to be "information-first." Headlines use tighter line heights and heavier weights to establish a clear hierarchy, while body text uses generous line spacing (1.5x) to ensure parents can easily read billing details and transaction history. On mobile, the scale shifts to prioritize screen real estate while keeping touch-friendly labels prominent.

## Layout & Spacing
This design system employs a **Fluid Grid** for mobile and a **Fixed Grid** (max-width 1200px) for web dashboard views.

- **Mobile:** Uses a single-column layout with a 16px side margin. Cards and buttons generally span the full width of the safe area.
- **Web:** Uses a 12-column grid. The sidebar is fixed at 280px, with the main content area expanding to fill the remainder up to the max width.
- **Rhythm:** An 8pt spacing system governs all margins and paddings. Component internal padding typically uses `sm` (8px) or `md` (16px), while layout sections use `lg` (24px) or `xl` (32px) to provide sufficient "breathing room" typical of modern fintech apps.

## Elevation & Depth
Depth is conveyed through **Ambient Shadows** and **Tonal Layers**. Following the "realistic student project" requirement, shadows are not overly complex but are used to indicate interactivity.

- **Surface Level (0dp):** The main background (#FFFFFF) or secondary sections (#F3F4F6).
- **Card Level (1dp):** White cards placed on #F3F4F6 backgrounds. These use a soft, diffused shadow: `0px 4px 12px rgba(0, 0, 0, 0.05)`.
- **Floating Level (2dp):** Used for modals and dropdown menus. These use a more pronounced shadow: `0px 8px 24px rgba(0, 0, 0, 0.1)`.
- **Dividers:** Used only when necessary to separate content within a card; 1px width in #E5E7EB.

## Shapes
The shape language is defined by a **Rounded** philosophy (Radius 2). This softens the "institutional" feel of school software, making it feel like a consumer-grade financial app.

- **Standard Elements:** Buttons, input fields, and small chips use a 0.5rem (8px) radius.
- **Containers:** Dashboard cards and modal windows use a 1rem (16px) radius to create a distinct, friendly container for information.
- **Interactive States:** Clicking or tapping a rounded element should trigger a subtle scale down (98%) or a slight color darken to provide tactile feedback.

## Components
- **Buttons:** Primary buttons are solid Teal (#028090) with white text. Secondary buttons are light gray (#F3F4F6) with teal text. Height is 48px for mobile accessibility.
- **Cards:** The central component of the app. Every "Tagihan" (Invoice) or "Riwayat" (History) item is a card with 16px internal padding and a 16px corner radius.
- **Input Fields:** Outlined style with a 1px #D1D5DB border. On focus, the border thickens to 2px and changes to the Primary Teal.
- **Status Chips:** Small badges with rounded-pill shapes. "Paid" uses a light green background with dark green text; "Unpaid" uses a light red background with dark red text.
- **Payment Method Selector:** Mimics the "Bank Mandiri Livin" style—large horizontal cards with the bank icon, name, and a chevron indicating it can be tapped to expand.
- **Progress Bar:** For "Total Paid" visuals, use a thick 8px rounded track in #F3F4F6 with a Teal fill to represent the percentage of the school year paid.