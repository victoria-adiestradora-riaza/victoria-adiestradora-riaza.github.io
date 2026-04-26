---
name: Victoria Sornosa Rueda Design System
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#424844'
  inverse-surface: '#303030'
  inverse-on-surface: '#f2f0f0'
  outline: '#727974'
  outline-variant: '#c1c8c3'
  surface-tint: '#466557'
  primary: '#163428'
  on-primary: '#ffffff'
  primary-container: '#2d4b3e'
  on-primary-container: '#99baa9'
  inverse-primary: '#adcebd'
  secondary: '#9a4529'
  on-secondary: '#ffffff'
  secondary-container: '#fc9170'
  on-secondary-container: '#742910'
  tertiary: '#312f27'
  on-tertiary: '#ffffff'
  tertiary-container: '#48453c'
  on-tertiary-container: '#b7b2a7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c8ead8'
  primary-fixed-dim: '#adcebd'
  on-primary-fixed: '#012116'
  on-primary-fixed-variant: '#2f4d40'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#ffb59e'
  on-secondary-fixed: '#3a0a00'
  on-secondary-fixed-variant: '#7b2e14'
  tertiary-fixed: '#e8e2d6'
  tertiary-fixed-dim: '#cbc6ba'
  on-tertiary-fixed: '#1e1c14'
  on-tertiary-fixed-variant: '#4a473e'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  headline-xl:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  section-padding: 80px
---

## Brand & Style

The design system is built to reflect the professional expertise and deep environmental connection of Victoria Sornosa Rueda. It balances the high-end, clinical precision of modern dog training with the rustic, soulful landscape of Riaza and Segovia. The personality is "The Empathetic Expert"—authoritative enough to provide security to dog owners, yet warm enough to foster a deep bond with animals.

The visual style follows a **Modern Minimalist** approach with **Tactile** influences. This is achieved through expansive whitespace (breathing room), sophisticated serif typography, and a color story rooted in the Spanish countryside. Every interface element should feel grounded, avoiding flashy digital-first trends in favor of an aesthetic that feels like it belongs in the natural world.

## Colors

The palette is a curated reflection of the Riaza landscape. The **Primary Green (#2D4B3E)** serves as the anchor, representing stability, nature, and professional growth. The **Secondary Terracotta (#D47152)** is used as a strategic accent color to draw attention to actions and highlights, evoking the warmth of local architecture and sun-baked earth.

**Tertiary Beige (#E8E2D6)** acts as the primary background surface, providing a softer, more organic alternative to pure white, which reduces eye strain and enhances the "premium" feel. **Neutral Gray (#4D4D4D)**, retained from the source inspiration, ensures high-contrast legibility for long-form educational content.

## Typography

This design system utilizes a high-contrast typographic pairing to bridge the gap between tradition and modern science. **Noto Serif** is used for all headings to provide an elegant, literary feel that conveys Victoria’s established authority.

**Manrope** is the workhorse for body text and functional UI. It was selected for its modern, balanced proportions and exceptional legibility at smaller sizes. Body text should maintain a generous line height (1.6) to facilitate an easy reading experience, especially for long-form training guides or testimonials.

## Layout & Spacing

The layout philosophy emphasizes "Atmospheric Space." Inspired by the vast open fields of Segovia, the design system utilizes a **Fixed Grid** (1200px max width) with wide margins to center the user’s focus. 

A vertical rhythm based on 8px increments ensures consistency, but the system encourages "breaking the grid" with high-quality, full-bleed imagery of dogs in nature. Large sections are separated by significant vertical padding (80px+) to prevent the interface from feeling cluttered, maintaining a sense of calm and order throughout the user journey.

## Elevation & Depth

To maintain a grounded and natural feel, the design system avoids harsh, artificial shadows. Instead, it uses **Tonal Layers** and **Low-Contrast Outlines**. 

Depth is achieved by placing elements on slightly varied neutral surfaces (e.g., a pure white card on a warm beige background). When shadows are necessary for interactivity (such as on buttons), they should be extremely diffused with a slight green or brown tint to mimic natural ambient occlusion found in the outdoors. Thin, 1px borders in a muted version of the primary green are preferred over heavy shadows for defining container boundaries.

## Shapes

The shape language is **Rounded (Level 2)**. This 0.5rem (8px) base radius softens the interface, making the brand feel more approachable and less "corporate." 

Interactive components like buttons use slightly more generous rounding (up to `rounded-xl` for pills) to create a friendly, "touchable" quality. Image containers should always feature consistent rounding to harmonize with the soft silhouettes of animals and natural landscapes.

## Components

### Buttons
Primary buttons use the Forest Green background with white text, utilizing a soft-pill shape. Secondary buttons use the Terracotta accent for urgent calls to action like "Book a Session." Text links should be underlined and use a semi-bold weight from the Manrope family.

### Cards
Cards are the primary container for services and blog posts. They should feature a thin, low-opacity border (#2D4B3E at 10% opacity) and no shadow. The header of the card should use Noto Serif, while the content uses Manrope.

### Input Fields
Fields are designed with a warm beige fill and a bottom-border-only focus state in primary green. This minimizes visual noise and aligns with the minimalist aesthetic.

### Chips & Tags
Tags for "Puppy Training," "Behavioral," or "Riaza Local" use the Terracotta color at 15% opacity with dark text to provide categorization without overwhelming the layout.

### Imagery
Images are considered a core component. All photography should feature natural lighting, avoiding studio backdrops. Focus on capturing the connection between dog and trainer within the local Spanish landscape. Use a subtle grain overlay on images to enhance the tactile, "natural" feel of the system.