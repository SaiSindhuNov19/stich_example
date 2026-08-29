---
name: Artisanal Earth
colors:
  surface: '#fff8f4'
  surface-dim: '#e0d9d4'
  surface-bright: '#fff8f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf2ed'
  surface-container: '#f4ede8'
  surface-container-high: '#eee7e2'
  surface-container-highest: '#e8e1dc'
  on-surface: '#1e1b18'
  on-surface-variant: '#4d463e'
  inverse-surface: '#33302d'
  inverse-on-surface: '#f7efea'
  outline: '#7e766d'
  outline-variant: '#cfc5bb'
  surface-tint: '#685c50'
  primary: '#685c50'
  on-primary: '#ffffff'
  primary-container: '#b8a99a'
  on-primary-container: '#483e32'
  inverse-primary: '#d4c4b4'
  secondary: '#5f5e5c'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfdc'
  on-secondary-container: '#636260'
  tertiary: '#695c4e'
  on-tertiary: '#ffffff'
  tertiary-container: '#b9a999'
  on-tertiary-container: '#493e31'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f1e0cf'
  primary-fixed-dim: '#d4c4b4'
  on-primary-fixed: '#221a10'
  on-primary-fixed-variant: '#504539'
  secondary-fixed: '#e5e2df'
  secondary-fixed-dim: '#c8c6c3'
  on-secondary-fixed: '#1c1c1a'
  on-secondary-fixed-variant: '#474745'
  tertiary-fixed: '#f1e0ce'
  tertiary-fixed-dim: '#d4c4b3'
  on-tertiary-fixed: '#231a0f'
  on-tertiary-fixed-variant: '#504538'
  background: '#fff8f4'
  on-background: '#1e1b18'
  surface-variant: '#e8e1dc'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 28px
    fontWeight: '400'
    lineHeight: '1.3'
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
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

This design system is crafted for a specialized marketplace dedicated to handmade ceramics and pottery. The brand personality is grounded, quiet, and deeply artisanal, emphasizing the tactile nature of clay and the human hand behind the craft. The target audience includes collectors, interior enthusiasts, and slow-living advocates who value quality over mass production.

The visual direction follows a **Minimalist Tactile** approach. It leverages generous whitespace to let the product photography breathe, while using a warm, monochromatic-leaning palette to evoke the feeling of a sun-drenched studio. The goal is to create a serene digital environment that mirrors the calm of a gallery, ensuring the user feels a sense of trust and permanence.

## Colors

The palette is derived from natural earth and mineral pigments. The seed color, a warm mid-tone taupe (`#B8A99A`), serves as the primary anchor for actions and highlights. 

- **Primary:** Warm Taupe. Used for primary call-to-actions and active states.
- **Secondary:** Soft Cream. Used for large surface areas and background sections to soften the UI.
- **Tertiary:** Muted Clay. Used for secondary UI elements, borders, and subtle accents.
- **Neutral:** Deep Charcoal. Reserved for typography and high-contrast icons to ensure legibility and a sense of "ink on paper."
- **Background:** Bone White. A slightly off-white base to prevent the digital "glare" of pure white, maintaining the organic feel.

## Typography

The typographic hierarchy relies on the contrast between the timeless, literary quality of **Noto Serif** and the modern, approachable clarity of **Plus Jakarta Sans**.

- **Headlines:** Use Noto Serif for all headings. The serif terminals echo the traditional tools used in pottery. High-level displays should use tighter letter spacing for an editorial look.
- **Body & UI:** Plus Jakarta Sans provides a friendly, legible experience for product descriptions, navigation, and labels.
- **Labels:** Use uppercase for labels and small buttons with slight tracking (letter spacing) to provide a sophisticated, gallery-label aesthetic.

## Layout & Spacing

This design system utilizes a **Fixed-Fluid Hybrid Grid**. Content is housed within a maximum width of 1280px for desktop to maintain readability, while using fluid percentages for smaller viewports.

- **Grid:** A 12-column grid on desktop, 6-column on tablet, and 2-column on mobile.
- **Rhythm:** An 8px base unit drives all spacing. For a "spacious" feel, prioritize the `lg` (48px) and `xl` (80px) units for vertical section margins.
- **Margins:** Generous outer margins (64px on desktop) ensure the product imagery feels like a curated exhibition rather than a crowded shop.

## Elevation & Depth

To maintain the "Safe" and artisanal aesthetic, depth is created through **Tonal Layers** and **Soft Ambient Shadows**. 

Avoid heavy, dark shadows. Instead, use:
1. **Low Elevation:** Subtle 1px borders in Muted Clay (`#8C7E6F`) with 20% opacity for card containers.
2. **Medium Elevation:** A wide-spread, low-opacity shadow (4% opacity Deep Charcoal) for hovered states or floating elements like navigation bars.
3. **Depth through Color:** Using the Secondary Cream (`#F5F2EF`) to differentiate the background of a section from the main page body, rather than using a shadow.

## Shapes

The shape language is inspired by the "soft edges" of hand-thrown pottery. Nothing is perfectly sharp, nor is it overly "bubbly" or geometric.

- **Corner Radii:** Following the `roundedness: 2` constraint, standard UI components (buttons, input fields) use a 0.5rem (8px) radius.
- **Large Components:** Product cards and hero images should use `rounded-lg` (1rem / 16px) to emphasize the soft, approachable nature of the brand.
- **Icons:** Use thin-stroke icons with rounded caps to match the body typography.

## Components

### Buttons
- **Primary:** Solid Warm Taupe with Bone White text. No shadow, 8px corner radius.
- **Secondary:** Transparent background with a 1px Muted Clay border.
- **Tertiary:** Text-only in Deep Charcoal with an underline on hover.

### Cards
Product cards are minimal. The image is the hero, featuring a `16px` corner radius. Details (Title, Artist, Price) are center-aligned beneath the image using Noto Serif for the title and Plus Jakarta Sans for the price.

### Input Fields
Soft Bone White backgrounds with a subtle 1px border. Focus states transition the border to Warm Taupe. Labels always sit above the field in uppercase `label-md` styling.

### Chips & Tags
Used for material types (e.g., "Stoneware", "Porcelain"). Small, pill-shaped containers with a Soft Cream background and Deep Charcoal text.

### Breadcrumbs & Lists
Highly minimal. Use arrows (`→`) or slashes (`/`) in Muted Clay. List items should have generous vertical padding (`16px`) to ensure a touch-friendly and breathable interface.