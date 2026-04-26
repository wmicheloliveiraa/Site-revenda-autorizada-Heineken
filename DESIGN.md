---
name: Serra Grande Premium Logistics
colors:
  surface: '#f6fbee'
  surface-dim: '#d6dccf'
  surface-bright: '#f6fbee'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f5e9'
  surface-container: '#eaf0e3'
  surface-container-high: '#e5eadd'
  surface-container-highest: '#dfe4d8'
  on-surface: '#181d15'
  on-surface-variant: '#404a3b'
  inverse-surface: '#2c322a'
  inverse-on-surface: '#edf3e6'
  outline: '#707a6a'
  outline-variant: '#bfcab7'
  surface-tint: '#106e09'
  primary: '#004b00'
  on-primary: '#ffffff'
  primary-container: '#006600'
  on-primary-container: '#88e274'
  inverse-primary: '#81db6e'
  secondary: '#bc000c'
  on-secondary: '#ffffff'
  secondary-container: '#e12823'
  on-secondary-container: '#fffbff'
  tertiary: '#404040'
  on-tertiary: '#ffffff'
  tertiary-container: '#575757'
  on-tertiary-container: '#cecdcd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#9cf987'
  primary-fixed-dim: '#81db6e'
  on-primary-fixed: '#002200'
  on-primary-fixed-variant: '#005300'
  secondary-fixed: '#ffdad5'
  secondary-fixed-dim: '#ffb4aa'
  on-secondary-fixed: '#410001'
  on-secondary-fixed-variant: '#930007'
  tertiary-fixed: '#e4e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#f6fbee'
  on-background: '#181d15'
  surface-variant: '#dfe4d8'
typography:
  display-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Be Vietnam Pro
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  section-padding: 48px
  card-gap: 24px
  unit-sm: 8px
  unit-md: 16px
---

## Brand & Style
The brand identity is rooted in the "Premium Industrial" aesthetic—combining the rugged reliability of large-scale logistics with the prestige of world-class beverage brands. It utilizes a **Corporate / Modern** style characterized by high-fidelity color execution, crisp photography, and a structured, authoritative layout.

The visual narrative focuses on trust and efficiency. It avoids excessive decoration in favor of clear information hierarchy, using deep greens and vibrant reds to signal brand alignment while maintaining a clean, white-space-heavy environment that feels professional and organized.

## Colors
The palette is dominated by "Heineken Green" (#006600), used as the primary action color and brand anchor. "Promotion Red" (#BC000C) acts as a high-impact secondary color for alerts, badges, and secondary brand highlights.

The neutral scale is carefully tuned with cool-toned greys and soft off-whites (#F9F9F9) to provide a "clean-room" backdrop for product photography. Text is rendered in a near-black (#1A1C1C) for maximum legibility, while decorative borders use a subtle grey-green tint (#E2E2E2) to harmonize with the primary brand color.

## Typography
The system relies exclusively on **Be Vietnam Pro**, a contemporary sans-serif that balances geometric efficiency with friendly terminals. 

- **Display levels** use an Extra Bold weight with negative letter spacing to create a powerful, "billboard" feel.
- **Body text** favors a generous line height (1.5-1.6) to ensure effortless reading of logistics and service details.
- **Labels** are frequently uppercased and tracked out when used in badges, or set in Bold at 14px for interactive UI elements.

## Layout & Spacing
The system uses a **Fixed Grid** approach for the main content areas, centered with a 1280px maximum width. A modular spacing scale based on 8px increments (4/8/16/24/48) ensures vertical rhythm.

Large sections are separated by significant white space (48px or more) to distinguish service offerings. The "Bento Grid" layout for products utilizes 24px gutters, allowing for a mix of large feature cards (spanning 2 columns) and standard product cards.

## Elevation & Depth
Depth is created through **Tonal Layers** and **Low-Contrast Outlines**. Surfaces are primarily flat, with elevation indicated by:

1.  **Ghost Borders:** Subtle 1px borders (#E2E2E2) define containers without heavy shadows.
2.  **Soft Shadows:** Interactive elements like cards and primary buttons utilize highly diffused, low-opacity shadows (e.g., `rgba(0, 102, 0, 0.08)`) that inherit the primary color's tint.
3.  **Hero Overlays:** Dark semi-transparent overlays (Black/50%) are used over photography to create a separate Z-layer for text legibility.

## Shapes
The shape language is **Rounded**, leaning towards a friendly but professional feel. 

- **Standard Cards:** 16px corner radius.
- **Feature/CTA Containers:** 24px corner radius.
- **Buttons & Inputs:** 8px corner radius for a sturdy, stable appearance.
- **Badges/Chips:** Full pill-shaped (999px) to contrast against the more rectangular cards.

## Components

### Buttons
- **Primary:** Solid green background, white text, 8px radius. Active state involves a 95% scale-down.
- **Secondary/Outline:** 1px border using the primary green or outline color, with text in the primary color.
- **Ghost:** No background, primary color text, used for less critical navigation.

### Cards
Cards are the primary organizational unit. They feature 1px borders (#E2E2E2), a 16px corner radius, and internal padding of 24px. Hover states should include a subtle lift (negative Y-offset) and a tinted green shadow.

### Inputs
Form fields use a white background with a 1px neutral border. On focus, the border transitions to the primary brand green with a subtle 1px glow. Labels are positioned above the field in Bold 12px caps.

### Badges
Small, pill-shaped markers used for status (e.g., "In Stock") or categories. They use high-contrast color pairings: Primary/On-Primary or Secondary/On-Secondary.

### Navigation
A sticky top bar with a clean 1px bottom border. It uses a bold weight for the active state and a medium weight for inactive links, with a simple underline indicator for the current page.