---
name: Executive Tech Portfolio
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#424754'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#727785'
  outline-variant: '#c2c6d6'
  surface-tint: '#005ac2'
  primary: '#0058be'
  on-primary: '#ffffff'
  primary-container: '#2170e4'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#4d5d73'
  on-tertiary: '#ffffff'
  tertiary-container: '#66768d'
  on-tertiary-container: '#fdfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-md:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter-sm: 16px
  gutter-md: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  max-width: 1280px
---

## Brand & Style
The design system is engineered for high-level technology executives and professional portfolios where clarity, precision, and authority are paramount. The brand personality is "Institutional Modernism"—a blend of corporate stability and cutting-edge technical proficiency.

The visual style follows a **Corporate / Modern** approach with a lean toward **Minimalism**. It prioritizes heavy white space, intentional alignment, and a sophisticated light-mode palette to evoke a sense of transparency and organized thought. The emotional response should be one of immediate trust and effortless navigation, positioning the user as a leader in their field.

## Colors
This design system utilizes a high-clarity light palette designed for readability and professional focus.

- **Primary (#3b82f6):** A vibrant Executive Blue used for primary actions, active states, and critical highlights.
- **Secondary (#0f172a):** Slate Navy, reserved for high-level headings and core branding elements to provide weight and contrast.
- **Tertiary (#64748b):** Muted Slate, used for secondary text and supportive iconography.
- **Neutral (#f8fafc):** The canvas. A crisp, cool-white background that ensures the interface feels airy and organized.

Surface containers should use `#ffffff` (White) to lift off the `#f8fafc` background, while borders should maintain a subtle `#e2e8f0` (Slate 200) to define boundaries without adding visual noise.

## Typography
Montserrat is the exclusive typeface for this design system, providing a geometric, clean, and confident architectural feel. 

Headlines utilize bold weights and tighter letter-spacing to convey authority. Body copy is set with generous line heights to ensure maximum legibility during long-form reading of technical case studies. Labels use increased letter-spacing and uppercase styling for a "status-driven" aesthetic typical of high-end dashboards.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop and a **Fluid Grid** on mobile.

- **Desktop:** A 12-column centered layout with a max-width of 1280px. Content is structured within 24px gutters.
- **Tablet:** 8-column layout with 24px gutters.
- **Mobile:** 4-column layout with 16px gutters and 20px side margins.

Spacing follows a strict 4px baseline grid. Use larger increments (64px, 80px, 120px) between major sections to emphasize the premium, spacious executive feel. Elements should be grouped using proximity: 8px for related items, 24px for distinct blocks.

## Elevation & Depth
In this light-themed design system, depth is communicated through **Tonal Layers** and **Ambient Shadows**.

1.  **Base Layer:** `#f8fafc` (Background).
2.  **Surface Layer:** `#ffffff` (White) cards and containers.
3.  **Elevation Level 1 (Low):** Used for standard cards. A subtle shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.1), 0 1px 2px -1px rgba(15, 23, 42, 0.1)`.
4.  **Elevation Level 2 (High):** Used for modals and dropdowns. A more pronounced, soft shadow: `0 10px 15px -3px rgba(15, 23, 42, 0.08)`.

Avoid heavy dark shadows. The goal is to make elements feel "floated" rather than "stamped" onto the page.

## Shapes
This design system employs a **Soft** (0.25rem) radius for standard UI components to maintain a professional, architectural edge without being overly aggressive.

- **Standard Buttons & Inputs:** 0.25rem (4px).
- **Cards & Larger Containers:** 0.5rem (8px).
- **Special Elements (Tags/Badges):** May use 1rem (16px) for distinct visual differentiation.

Consistency in corner radii reinforces the systematic, technical nature of the brand.

## Components
- **Buttons:** Primary buttons use a solid Primary Blue (#3b82f6) with White text. Secondary buttons use a Slate Navy (#0f172a) outline with a 1px border.
- **Inputs:** Use a White background with a Slate 200 (#e2e8f0) border. On focus, the border transitions to Primary Blue (#3b82f6) with a 2px outer glow.
- **Cards:** Pure White (#ffffff) backgrounds with Level 1 shadows. Headers within cards should use Slate Navy for the title and Muted Slate for subtitles.
- **Chips/Badges:** Small, low-contrast pills. Light-mode badges use a background of Slate 100 (#f1f5f9) with Slate Navy text.
- **Lists:** Clean dividers using 1px Slate 100 lines. Hover states for list items should use a subtle background shift to #f8fafc.
- **Data Tables:** High-density, using Slate Navy for headers and clear row separation.