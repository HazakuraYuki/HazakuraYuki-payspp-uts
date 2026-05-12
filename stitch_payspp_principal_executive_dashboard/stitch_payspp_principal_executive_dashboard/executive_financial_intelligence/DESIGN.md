---
name: Executive Financial Intelligence
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
  secondary: '#575e70'
  on-secondary: '#ffffff'
  secondary-container: '#d9dff5'
  on-secondary-container: '#5c6274'
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
  secondary-fixed: '#dce2f7'
  secondary-fixed-dim: '#c0c6db'
  on-secondary-fixed: '#141b2b'
  on-secondary-fixed-variant: '#404758'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb782'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#6f3801'
  background: '#f6fafb'
  on-background: '#181c1d'
  surface-variant: '#dfe3e4'
typography:
  display-metric:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
  data-table:
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
  grid_columns: '12'
  gutter: 1.5rem
  margin_desktop: 2.5rem
  margin_mobile: 1rem
  section_gap: 2rem
  container_max_width: 1440px
---

## Brand & Style

The design system is engineered to project **authority, precision, and fiscal clarity**. It bridges the gap between high-end Business Intelligence (BI) tools and educational management systems, specifically tailored for Indonesian private school boards and principals.

The aesthetic follows a **Modern Corporate** approach with a focus on **Financial Transparency**. Key visual pillars include:
- **Executive Sophistication:** A blend of professional teal and neutral surfaces that minimize cognitive load.
- **Analytical Depth:** Subtle use of glassmorphism and multi-layered elevation to differentiate between high-level summaries and granular data.
- **Indonesian Excellence:** A clean, organized layout that reflects the administrative rigor of top-tier private institutions.
- **Trust-Centric:** Precise typography and a rigid grid system to ensure financial data is perceived as accurate and immutable.

## Colors

The color palette is anchored by **Professional Teal (#028090)**, selected for its balance of innovation and stability. 

- **Primary:** Used for primary actions, navigation highlights, and brand reinforcement.
- **Semantic Statuses:** These are critical for financial health monitoring. 
    - **Healthy (Green):** Successful payments and surplus.
    - **Warning (Orange):** Approaching deadlines or pending approvals.
    - **Critical (Red):** Overdue accounts and budget deficits.
    - **Active (Blue):** General information and current processing states.
- **Neutral Scale:** Utilizes a cool-gray spectrum to maintain a clean, "Swiss-style" enterprise feel, ensuring that colorful data visualizations remain the focal point.

## Typography

The design system utilizes **Inter** for its exceptional legibility in data-dense environments and neutral character. 

- **Metric Hierarchy:** Large "Display Metric" styles are used for top-level financial totals (e.g., Total Revenue, Outstanding Balance).
- **Data Tables:** Table content uses a slightly smaller, medium-weight font to maximize information density without sacrificing readability.
- **Letter Spacing:** Headlines utilize tight tracking for a premium, "editorial" look, while labels and small data points use expanded tracking to ensure clarity in complex reports.
- **Indonesian Language Support:** The system is optimized for Indonesian sentence lengths, particularly in long administrative labels.

## Layout & Spacing

This design system employs a **12-column responsive fluid grid** with a maximum container width of 1440px to prevent excessive line lengths on ultra-wide executive monitors.

- **Data Density:** Spacing is tighter within analytical cards (8px units) to allow for more visual data, while the layout between major sections is generous (32px+) to provide "visual breathing room" for executive decision-making.
- **Sidebar Architecture:** A fixed 280px left navigation provides persistent access to school departments, with a secondary "utility" rail for quick actions (notifications, search).
- **Mobile Reflow:** On mobile devices, the 12-column grid collapses to a single column, with cards stackable by priority (Metrics first, then Charts, then Tables).

## Elevation & Depth

To achieve an executive feel, depth is communicated through **Subtle Layering** rather than heavy shadows.

- **Primary Surface:** The background remains a flat, off-white neutral.
- **Dashboard Cards:** Elevated using a "Soft Ambient" shadow (0px 4px 20px rgba(0,0,0,0.04)) and a 1px border in a slightly darker neutral.
- **Glassmorphism Accents:** Used sparingly for sticky headers, modal overlays, and "Fly-out" filters. These surfaces use a backdrop blur of 12px and a 60% opacity white fill to maintain context of the underlying data.
- **Interactive States:** Buttons and clickable cards exhibit a subtle lift (increased shadow) and a very slight gradient shift to indicate interactivity.

## Shapes

The design system adopts a **Rounded** aesthetic to soften the complexity of financial data.

- **Standard Cards:** 0.5rem (8px) corner radius.
- **Large Container/Sections:** 1rem (16px) corner radius to create a distinct frame for dashboard modules.
- **Buttons & Chips:** Pill-shaped (3rem) for action items to distinguish them from data-holding containers.
- **Data Points:** Heatmap cells and bar chart ends should maintain a 2px-4px radius to align with the overall soft-professional visual language.

## Components

### Premium Analytics Cards
Cards should feature a header with a "Contextual Help" icon, a large Display Metric, and a "Trend Indicator" (small sparkline or percentage change). Backgrounds may feature a very subtle, low-contrast gradient (e.g., White to #F3F4F6) to add depth.

### Complex Data Tables
- **Header:** Sticky headers with integrated sorting and column-specific filtering.
- **Rows:** Zebra-striping is avoided in favor of subtle border-bottoms. On-hover, rows should highlight in a very pale teal (#F0F9FA).
- **Cell Types:** Support for status badges (chips), progress bars (for payment collection), and avatar groups (for student lists).

### Sophisticated Navigation
The sidebar should use the Primary Teal for the active state background, with high-contrast white text. Icons should be "Duotone" or "Thin-line" to maintain a modern BI feel.

### Advanced Chart Treatments
- **Line Charts:** Use "monotone" curves with area gradients beneath the line.
- **Donut Charts:** Use thick strokes with center-aligned "Total" metrics.
- **Heatmaps:** Use a stepped-color scale using the Primary Teal at varying opacities to represent tuition collection density across different grade levels.

### Executive Controls
Date pickers and filters should be grouped in a persistent "Global Filter Bar" at the top of the dashboard, allowing principals to toggle between different academic years or branches instantly.