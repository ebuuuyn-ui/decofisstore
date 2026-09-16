---
name: Decofis Ethos
colors:
  surface: '#f9f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f9f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f5'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e4'
  on-surface: '#1a1c1d'
  on-surface-variant: '#4c4546'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f0f2'
  outline: '#7e7576'
  outline-variant: '#cfc4c5'
  surface-tint: '#5e5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1b'
  on-primary-container: '#848484'
  inverse-primary: '#c6c6c6'
  secondary: '#006b57'
  on-secondary: '#ffffff'
  secondary-container: '#7ef8d7'
  on-secondary-container: '#00725d'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1b1b'
  on-tertiary-container: '#848484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#7ef8d7'
  secondary-fixed-dim: '#5fdbbb'
  on-secondary-fixed: '#002019'
  on-secondary-fixed-variant: '#005141'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1b1b1b'
  on-tertiary-fixed-variant: '#474747'
  background: '#f9f9fb'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e4'
  surface-white: '#FFFFFF'
  glass-bg: rgba(255, 255, 255, 0.7)
  border-subtle: rgba(0, 0, 0, 0.08)
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
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
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 80px
---

## Brand & Style
The design system embodies a premium, Apple-inspired aesthetic tailored for high-end office ergonomics. The brand personality is professional and futuristic, yet deeply rooted in physical comfort and clarity. 

The visual style is a fusion of **Minimalism** and **Glassmorphism**. It prioritizes extreme clarity through generous whitespace and a restricted color palette, using translucent materials to signify depth and modern sophistication. Every interface element should feel as precision-engineered as the furniture it represents. High-quality, bright, and airy photography serves as the primary visual texture, allowing the furniture pieces to remain the focal point.

## Colors
The palette is intentionally restrained to emphasize a "studio" feel. 
- **Primary:** Deep Black (#000000) is used exclusively for high-contrast typography and primary action icons to ensure maximum readability and a premium feel.
- **Backgrounds:** A tiered system using Pure White (#FFFFFF) for primary cards and content surfaces, and Off-White (#F5F5F7) for global page backgrounds to provide subtle contrast.
- **Accents:** The Brand Teal (#39BB9D) is used sparingly as a functional accent—status indicators, success states, or subtle hover highlights—to prevent it from overwhelming the monochromatic luxury.
- **Glassmorphism:** Navigation bars and overlays utilize a 70% opaque white with a heavy (30px+) backdrop blur to create a sense of lightness and spatial awareness.

## Typography
Manrope is selected for its geometric purity and modern proportions, echoing the precision of ergonomic design. 

Hierarchy is established through weight and scale rather than color shifts. 
- **Headlines:** Use Semi-Bold (600) and Bold (700) weights with tighter letter spacing to create a strong, authoritative presence.
- **Body:** Use Regular (400) weight for long-form reading, ensuring high legibility against white surfaces.
- **Labels:** Small caps or slightly increased letter spacing (0.05em) should be used for metadata and utility labels to maintain a clean, organized grid.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop to maintain the "editorial gallery" feel, while transitioning to a fluid, high-margin model for mobile.

- **Grid:** A 12-column grid is used for desktop (1440px max width) with generous 80px side margins to isolate content and evoke a premium atmosphere.
- **Rhythm:** An 8px linear scale governs all padding and margins. 
- **Whitespace:** Use "intentional emptiness." Product cards and sections should have vertical padding of at least 80px to 120px on desktop to allow the furniture silhouettes to breathe.

## Elevation & Depth
Depth is created through **Tonal Layers** and **Backdrop Blurs** rather than traditional heavy shadows.

- **Surfaces:** Use `#FFFFFF` for the highest elevation elements (cards, active inputs) against the `#F5F5F7` base.
- **Shadows:** Only use extremely subtle, long-range ambient shadows for floating elements (e.g., `0px 20px 40px rgba(0,0,0,0.04)`). The shadow should feel like a soft glow rather than a dark silhouette.
- **Glass:** Modal overlays and navigation bars use `backdrop-filter: blur(20px)` combined with a subtle `1px` inner border of `rgba(255,255,255,0.5)` to simulate the edge of a glass pane.

## Shapes
The shape language is "Organic Geometric." Elements use a base roundedness of 12px-16px to reflect the ergonomic curves of high-end seating. 

- **Primary Cards:** 20px (`rounded-xl`) corner radius for large content blocks.
- **Buttons & Inputs:** 12px (`rounded-md`) corner radius.
- **Interactive States:** Subtle scale-down transforms (98%) on press to provide tactile feedback without visual clutter.

## Components
- **Buttons:** Primary buttons are solid black with white text. Secondary buttons are ghost-style with a 1.5px black border or a subtle gray fill.
- **Inputs:** Minimalist fields with a light gray background (`#F5F5F7`) that transition to white on focus. Labels should stay above the field in a small-cap `label-md` style.
- **Cards:** No borders. Use the elevation strategy (white card on gray background) with 20px rounded corners. Images should occupy the top 70% of the card with zero internal padding to the card edges.
- **Chips:** Small, pill-shaped tags used for "In Stock" or "Ergonomic" categories, using a light gray fill and black text.
- **Navigation:** A persistent top-bar with a glassmorphism effect. Logo is centered or left-aligned in black, with navigation links in `label-md` weight.
- **Product Hotspots:** Use subtle, pulsing white circles on furniture images to allow users to click and see specific ergonomic features.