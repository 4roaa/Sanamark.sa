---
name: Sanamark Architectural & Health Logic
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
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#855300'
  on-secondary: '#ffffff'
  secondary-container: '#fea619'
  on-secondary-container: '#684000'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#0b1c30'
  on-tertiary-container: '#75859d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  title-sm:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-main:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-bold:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

This design system establishes a visual bridge between the precision of high-end construction and the reliability of modern healthcare. The brand personality is authoritative yet innovative, designed to evoke a sense of structural integrity and clinical excellence. 

The visual style follows a **Corporate / Modern** aesthetic, utilizing high-density layouts and clear information hierarchies. It prioritizes clarity and "The Mark of Distinction" through intentional whitespace and premium finishes. The interface avoids unnecessary flourishes, focusing instead on structural balance and functional beauty to appeal to enterprise-level stakeholders.

## Colors

The palette is anchored by **Deep Navy (Charcoal)**, symbolizing the strength of steel beams and the seriousness of medical institutions. **Bright Gold/Orange** is used surgically as a "precision accent" to highlight critical actions, progress indicators, and innovation markers. 

- **Primary:** Deep Navy for headers, primary buttons, and structural navigation.
- **Secondary:** Gold/Orange for high-priority CTAs, status highlights, and "Distinction" markers.
- **Background:** A pristine, clean white environment to ensure medical-grade legibility.
- **Neutral:** Slate grays used for secondary text, borders, and subtle layout divisions.

## Typography

The typography system is optimized for bilingual excellence (Arabic/English). **Manrope** provides a geometric, modern structure for headlines that echoes architectural blueprints. **Inter** is utilized for body text and data-heavy interfaces, ensuring maximum readability in both healthcare records and construction manifests.

For Arabic implementation, use **IBM Plex Sans Arabic** or **Tajawal**. Maintain a consistent weight-to-size ratio between scripts. Headlines should remain bold and structured, while body copy maintains ample line height (1.6) to prevent visual fatigue in professional documentation.

## Layout & Spacing

This design system employs a **Fixed Grid** philosophy for desktop (12 columns) and a fluid layout for mobile. The spacing rhythm is based on a 4px baseline grid, ensuring mathematical precision—a nod to engineering standards.

Generous margins (40px+) are used between major sections to emphasize the "Enterprise" feel, preventing the UI from feeling cluttered. Elements within cards should follow a strict internal padding of 24px (lg) to maintain a spacious, premium aesthetic.

## Elevation & Depth

Visual hierarchy is achieved through **Ambient Shadows** and **Tonal Layers**. Shadows are used sparingly to signify "lift" on interactive components like cards and modals. 

The shadow profile is extremely soft: a wide blur (20px-40px) with very low opacity (4-8%) using the primary Navy color as a tint rather than pure black. This creates a "floating" effect for high-priority information without breaking the clean, white-space-driven aesthetic. Backgrounds use very subtle slate-50 offsets to distinguish between the page surface and the content containers.

## Shapes

The shape language reflects "Subtle Softness." While the brand is strong and structural, **Soft** corners (4px to 8px) are used to make the interface feel modern and accessible, particularly for the healthcare aspect of the business.

- **Buttons/Inputs:** 4px (Soft) for a precision-engineered look.
- **Cards/Containers:** 8px (Rounded-lg) to provide a gentle container for complex data.
- **Feature Icons:** Encapsulated in 12px (Rounded-xl) frames to create the "Mark of Distinction."

## Components

### Buttons & Controls
Primary buttons use the Deep Navy background with white text, featuring a subtle 1px inner border for depth. Secondary buttons utilize the Gold/Orange accent exclusively for text or outlines to signify innovation.

### The 'Mark of Distinction' Cards
Specialized cards for key sections feature a Gold top-border (2px) and a distinctive icon set. Icons are line-based (2pt stroke) with a "dual-tone" style, where the primary Navy is the main color and Gold is used for a single highlight element within the icon.

### Input Fields & Lists
Forms use a "Clinical Clean" style: white backgrounds with 1px Slate-200 borders. Focus states transition the border to Gold. Data lists use alternating row highlights in a very faint Slate-50 to manage complex construction or patient data.

### Progress & Indicators
Linear progress bars for construction milestones or health goals use a Gold-to-Orange gradient, providing a sense of momentum and "energy" against the stable Navy framework.