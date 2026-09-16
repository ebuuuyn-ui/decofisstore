---
name: Modern Atelier
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#3d4945'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#6d7a75'
  outline-variant: '#bccac3'
  surface-tint: '#006b57'
  primary: '#006b57'
  on-primary: '#ffffff'
  primary-container: '#39bb9d'
  on-primary-container: '#004638'
  inverse-primary: '#5fdbbb'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#5e5e5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#a8a7a7'
  on-tertiary-container: '#3c3d3d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#7ef8d7'
  primary-fixed-dim: '#5fdbbb'
  on-primary-fixed: '#002019'
  on-primary-fixed-variant: '#005141'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e4e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
  deep-teal: '#2E947D'
  slate-gray: '#333333'
  soft-border: '#E5E7EB'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Montserrat
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
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
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

This design system embodies the precision and reliability of premium office furniture manufacturing. The brand personality is professional, architectural, and highly organized, catering to corporate decision-makers and architects who value ergonomics and craftsmanship.

The visual style is **Corporate / Modern** with a focus on high-end minimalism. It prioritizes clarity and structure, using generous whitespace to allow product photography to breathe. The aesthetic suggests stability through a grounded grid system while maintaining a forward-thinking feel through sharp, contemporary accents and technical details.

## Colors

The palette is anchored by a vibrant "Decofis Teal" (#39BB9D), which serves as the primary action color and brand identifier. This is balanced by a dominant use of neutral grays and deep blacks to establish a high-end corporate atmosphere.

- **Primary:** Use for key CTAs, active states, and subtle branding accents.
- **Secondary:** Deep carbon black for text and high-contrast UI elements, providing a grounded foundation.
- **Tertiary:** Mid-tone grays used for secondary information and iconography.
- **Neutral:** Off-white surfaces and light gray borders ensure the interface feels airy and sophisticated, avoiding the harshness of pure white backgrounds in large areas.

## Typography

The typography strategy pairs the geometric strength of **Montserrat** for headlines with the exceptional legibility of **Inter** for body text. 

Headlines should utilize tighter letter-spacing and bold weights to convey authority and architectural structure. Body copy is optimized for readability with generous line heights. Labels use an uppercase treatment with increased tracking (letter-spacing) to create a clean, "catalog" feel reminiscent of architectural blueprints or technical specifications.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop to maintain a premium, editorial feel, while transitioning to a fluid system for mobile.

- **Desktop:** 12-column grid with a 1280px max-width. Use wide 48px margins to frame content as a gallery.
- **Rhythm:** An 8px base unit governs all spacing. Vertical "stack" spacing should be generous between sections (48px+) to emphasize product craftsmanship.
- **Alignment:** Consistent left-alignment is preferred for text blocks to maintain a professional, structured appearance. Use staggered layouts for product showcases to create a dynamic visual flow.

## Elevation & Depth

To maintain a clean and professional aesthetic, this design system avoids heavy shadows. Depth is primarily conveyed through **Tonal Layers** and **Low-contrast Outlines**.

- **Surfaces:** Use `#F8F9FA` for the primary background and `#FFFFFF` for cards or elevated containers.
- **Outlines:** Define boundaries with 1px solid borders in `soft-border` (#E5E7EB). This creates a technical, precise look.
- **Subtle Depth:** Where elevation is necessary (e.g., hover states on product cards), use a very soft, highly diffused shadow: `0px 10px 30px rgba(0, 0, 0, 0.04)`.

## Shapes

The shape language is "Soft" (0.25rem / 4px), mirroring the subtle curves found in ergonomic office furniture. This maintains a professional and structural feel without appearing overly aggressive or clinical.

- **Buttons & Inputs:** Use a 4px corner radius.
- **Product Cards:** Use an 8px radius (`rounded-lg`) to give them a distinct, tactile quality.
- **Icons:** Use linear icons with a 2px stroke weight to match the architectural precision of the typography.

## Components

- **Buttons:** Primary buttons use a solid Teal background with white text. Secondary buttons use a slate-gray outline. High-emphasis CTAs should utilize Montserrat in bold.
- **Input Fields:** Use a 1px `soft-border` with a subtle gray background. On focus, the border should transition to Teal.
- **Cards:** Product cards should be minimal, featuring a large high-quality image on a light neutral background, with text contained in a white section below.
- **Chips/Badges:** Use for product categories or "In Stock" status. Keep these small, using `label-sm` typography and subtle background fills.
- **Lists:** Use clean, hairline dividers between list items. Icons should be monochrome (Teal or Slate-Gray).
- **Specialty Components:** Include a "Spec-Sheet" component—a structured data table with high contrast and monospace-leaning labels—to emphasize technical furniture details.