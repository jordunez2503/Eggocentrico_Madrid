---
name: Eggocentrico
colors:
  surface: '#fbf9f1'
  surface-dim: '#dcdad2'
  surface-bright: '#fbf9f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f4ec'
  surface-container: '#f0eee6'
  surface-container-high: '#eae8e0'
  surface-container-highest: '#e4e3db'
  on-surface: '#1b1c17'
  on-surface-variant: '#4d4732'
  inverse-surface: '#30312c'
  inverse-on-surface: '#f3f1e9'
  outline: '#7e775f'
  outline-variant: '#d0c6ab'
  surface-tint: '#705d00'
  primary: '#705d00'
  on-primary: '#ffffff'
  primary-container: '#ffd700'
  on-primary-container: '#705e00'
  inverse-primary: '#e9c400'
  secondary: '#934b19'
  on-secondary: '#ffffff'
  secondary-container: '#ffa26a'
  on-secondary-container: '#783603'
  tertiary: '#9f402d'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffcfc5'
  on-tertiary-container: '#a0402d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe16d'
  primary-fixed-dim: '#e9c400'
  on-primary-fixed: '#221b00'
  on-primary-fixed-variant: '#544600'
  secondary-fixed: '#ffdbc9'
  secondary-fixed-dim: '#ffb68c'
  on-secondary-fixed: '#321200'
  on-secondary-fixed-variant: '#753401'
  tertiary-fixed: '#ffdad3'
  tertiary-fixed-dim: '#ffb4a5'
  on-tertiary-fixed: '#3e0500'
  on-tertiary-fixed-variant: '#802918'
  background: '#fbf9f1'
  on-background: '#1b1c17'
  surface-variant: '#e4e3db'
typography:
  display-lg:
    fontFamily: Quicksand
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Quicksand
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Quicksand
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Quicksand
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Be Vietnam Pro
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

The design system embodies a "Morning After" energy—vibrant, slightly eccentric, and deeply comforting. It targets urban brunch enthusiasts and specialty coffee lovers who value personality over corporate perfection. 

The aesthetic is a blend of **Modern Minimalism** and **Tactile warmth**. It utilizes heavy whitespace to let high-fidelity food photography breathe, while injecting "No Rules" playfulness through organic, asymmetric shapes and a "sunny-side-up" disposition. The UI should feel soft to the touch, approachable, and highly appetizing, evoking the sensory experience of a steaming latte and a perfectly poached egg.

## Colors

The palette is anchored by "Yolk Gold" (#FFD700), used strategically for primary actions and brand moments. The "Creamy Canvas" (#FFFDF5) serves as the universal background to maintain warmth without the sterile feel of pure white.

- **Primary (Yolk):** High energy, used for buttons, highlights, and active states.
- **Secondary (Espresso):** A deep warm brown used for primary text and grounding elements.
- **Tertiary (Terracotta):** Used for accents, secondary buttons, and nutritional highlights.
- **Neutral:** Warm off-whites and soft taupes for surfaces and containers to maintain a soft, organic feel.

## Typography

This design system utilizes **Quicksand** for all display and heading roles to reinforce the friendly, rounded brand character. Its soft terminals mirror the "organic shape" philosophy. 

**Be Vietnam Pro** is used for body copy and UI labels to ensure contemporary legibility and a clean, professional counter-balance to the playful headings. Editorial moments should favor `display-lg` with tight tracking to create a bold, "billboard" effect.

## Layout & Spacing

The layout philosophy follows a **Fluid Grid** with generous margins to mimic a high-end physical menu. 

- **Desktop:** 12-column grid with wide 40px margins to create a sense of luxury and space. 
- **Mobile:** 4-column grid with 16px margins.
- **Rhythm:** Use an 8px base unit. Component internal padding should be generous (24px+) to maintain the "airy" brunch feel. 

Large-scale food photography should frequently break the grid or use asymmetric "blob" masks to reinforce the "no rules" brand pillar.

## Elevation & Depth

Depth is achieved through **Ambient Shadows** and **Tonal Layering** rather than hard borders.

- **Shadows:** Use extremely soft, diffused shadows (Blur: 30px+, Opacity: 4-8%) with a slight warm tint (#8B4513) to make elements feel like they are resting on a tablecloth.
- **Surfaces:** Use subtle shifts in cream/off-white tones to separate sections. Avoid pure black shadows at all costs.
- **Photography:** Images should feel layered, sometimes overlapping container edges to create a 3D, tactile experience.

## Shapes

The shape language is dominated by **high-radius curves** and **organic blobs**. 

- **Standard Elements:** Use `rounded-lg` (1rem) for cards and input fields.
- **Buttons/Interactive:** Use `rounded-xl` (1.5rem) or full pill-shapes to invite clicking.
- **Specialty Shapes:** Use non-uniform border-radius (e.g., `60% 40% 30% 70%`) for decorative image masks and background accents to evoke the shape of a cracked egg or spilled milk.

## Components

- **Buttons:** Primary buttons use "Yolk Gold" with dark "Espresso" text. They should have a subtle "squish" animation (scale down to 0.96) on click.
- **Cards:** Cards should have no borders; instead, use a soft ambient shadow and a slightly lighter cream background than the main page.
- **Chips/Filters:** Use pill-shaped outlines in Terracotta for unselected states, and solid Yolk for active states.
- **Input Fields:** Thick 2px borders in a soft Taupe, moving to Yolk on focus. Label text should always be visible (no floating labels) to keep the "friendly/accessible" vibe.
- **Lists:** Menu items should feature a circular thumbnail of the dish, with the price highlighted in a Terracotta-colored Quicksand font.
- **Menu Specials:** Highlighted using the asymmetric "blob" mask technique to make them stand out from the standard grid.