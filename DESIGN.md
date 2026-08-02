---
name: Serene Sanctuary
colors:
  surface: '#fff8f5'
  surface-dim: '#e1d8d4'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2ed'
  surface-container: '#f5ece7'
  surface-container-high: '#efe6e2'
  surface-container-highest: '#e9e1dc'
  on-surface: '#1e1b18'
  on-surface-variant: '#434843'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efea'
  outline: '#737872'
  outline-variant: '#c3c8c1'
  surface-tint: '#506354'
  primary: '#334537'
  on-primary: '#ffffff'
  primary-container: '#4a5d4e'
  on-primary-container: '#c0d5c2'
  inverse-primary: '#b7ccb9'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#41423e'
  on-tertiary: '#ffffff'
  tertiary-container: '#595955'
  on-tertiary-container: '#d1d0cb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d3e8d5'
  primary-fixed-dim: '#b7ccb9'
  on-primary-fixed: '#0e1f13'
  on-primary-fixed-variant: '#394b3d'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#e4e2dd'
  tertiary-fixed-dim: '#c8c6c2'
  on-tertiary-fixed: '#1b1c19'
  on-tertiary-fixed-variant: '#474744'
  background: '#fff8f5'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
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
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style
The design system is centered on the concept of "Architectural Serenity." It balances the ancient discipline of Yoga with a modern, high-end boutique aesthetic. The personality is expert yet welcoming, achieved through a Minimalist style that prioritizes generous whitespace and a rhythmic, breathable layout. 

Visual cues draw from modern spiritualism—using light as a material, soft transitions, and a focus on essentialism. The interface should feel like a physical sanctuary: quiet, premium, and intentional. Every element must serve a purpose, eliminating visual noise to reduce cognitive load and evoke an immediate sense of calm in the practitioner.

## Colors
The palette utilizes a "Light Premium" foundation to create a sense of expansive space.
- **Primary (Sage Green):** Used for primary actions, success states, and subtle brand accents. It represents growth and groundedness.
- **Secondary (Muted Gold):** Reserved for high-end decorative elements, premium tier indicators, and specialized call-outs.
- **Surface (Ivory & Warm Beige):** The background is never pure white; use `tertiary` for the main canvas and a slightly deeper beige for containers to maintain warmth.
- **Neutral (Charcoal):** Used for typography to ensure high contrast and accessibility without the harshness of pure black.

## Typography
The typography strategy pairings a sophisticated, high-contrast serif for editorial impact with a functional, modern sans-serif for clarity.
- **Headlines:** Use `Playfair Display`. It provides the "traditional yet modern" prestige required for a premium studio. Maintain tight letter-spacing on larger sizes.
- **Body:** Use `Manrope`. Its geometric yet friendly terminals ensure readability in class descriptions and long-form wellness content.
- **Labels:** Use uppercase `Manrope` with increased letter-spacing for small metadata, navigation items, and overlines to create a rhythmic, structured feel.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop to maintain a controlled, gallery-like presentation. 
- **Rhythm:** Use an 8px base unit. Vertical rhythm should be exaggerated—don't be afraid of "wasted" space; in this design system, space equals luxury.
- **Desktop:** 12-column grid with a 1200px max-width.
- **Mobile:** 4-column grid with generous side margins to prevent the content from feeling "cramped" against the screen edges.
- **Section Breaks:** Use large vertical padding (`section-gap`) to separate different types of content (e.g., class schedules vs. instructor bios), allowing the user to focus on one thought at a time.

## Elevation & Depth
This design system avoids heavy shadows in favor of **Tonal Layers** and **Ambient Depth**.
- **Surface Strategy:** Use subtle shifts in background color (e.g., Ivory to soft Warm Beige) to define hierarchy rather than physical height.
- **Shadows:** When necessary for interactivity (like a hovered card), use a single, ultra-diffused shadow: `0 20px 40px rgba(74, 93, 78, 0.05)`. The tint should match the Primary Sage color to keep the shadow feeling organic.
- **Glassmorphism:** Use sparingly for sticky navigation bars. A 20px backdrop blur with a 70% opacity Ivory tint creates a soft, frosted effect that feels like morning mist.

## Shapes
The shape language is "Organic Geometric." 
- **Radius:** Standard elements use a 0.5rem (8px) radius to feel approachable but structured. 
- **Large Elements:** Featured imagery and main cards should use `rounded-xl` (1.5rem) to soften the overall visual impact of the screen.
- **Buttons:** Use fully pill-shaped (rounded-full) styling for primary calls to action to evoke a "pebble-like," tactile smoothness.

## Components
- **Buttons:** 
  - *Primary:* Pill-shaped, Sage Green background, white text. No border.
  - *Secondary:* Pill-shaped, transparent background, thin 1px border in Sage Green or Muted Gold.
- **Cards:** 
  - Use a warm beige background with `rounded-xl` corners. 
  - Padding should be generous (min 32px). 
  - Avoid borders; use soft ambient shadows on hover to indicate interactivity.
- **Navigation:** 
  - Minimalist top bar. Links use `label-md` typography.
  - Active states should be indicated by a small, centered dot in Muted Gold beneath the text rather than an underline.
- **Input Fields:** 
  - Soft beige fills with a bottom-border only for a "boutique stationery" feel, or a fully rounded border with very light opacity.
- **Chips/Badges:** 
  - Used for class difficulty (Beginner, Advanced). Use high-tracking `label-md` text and subtle tinted backgrounds (e.g., 10% opacity Sage).
- **Interactive State:** 
  - All hover transitions should be slow (300ms+) and use a "cubic-bezier" easing to feel graceful and fluid, mimicking the movement of Yoga.