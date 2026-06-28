---
name: Lumina Boutique Aesthetic
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#4f4443'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#817473'
  outline-variant: '#d2c3c1'
  surface-tint: '#6f5957'
  primary: '#6f5957'
  on-primary: '#ffffff'
  primary-container: '#f4d7d4'
  on-primary-container: '#725c5a'
  inverse-primary: '#dcc0bd'
  secondary: '#615b71'
  on-secondary: '#ffffff'
  secondary-container: '#e5dcf6'
  on-secondary-container: '#665f75'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffda6c'
  on-tertiary-container: '#775e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f9dcd9'
  primary-fixed-dim: '#dcc0bd'
  on-primary-fixed: '#271816'
  on-primary-fixed-variant: '#564240'
  secondary-fixed: '#e7def8'
  secondary-fixed-dim: '#cbc3dc'
  on-secondary-fixed: '#1d192b'
  on-secondary-fixed-variant: '#494458'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
  button-text:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  base: 8px
  container-padding: 24px
  section-gap: 80px
  element-gap: 16px
  grid-columns: '12'
  grid-gutter: 24px
---

## Brand & Style

The design system is anchored in "Boutique Minimalism"—a philosophy that balances clinical precision with high-end hospitality. It targets an aspirational audience seeking a sanctuary for self-care, evoking feelings of serenity, cleanliness, and warmth. 

The aesthetic is heavily influenced by modern beauty editorial styles: expansive whitespace, deliberate composition, and a focus on tactile softness. We avoid the clinical coldness of traditional spas by introducing warm organic tones and high-fashion typography. The visual language is flat and honest, eschewing complex effects like glassmorphism in favor of clear hierarchy and impeccable spacing.

## Colors

The palette is strictly curated to evoke a "clean beauty" sensation. 
- **Primary (Petal Pink):** Used for key brand moments and soft UI backgrounds.
- **Secondary (Soft Lavender):** Used sparingly for interactive highlights or category distinction.
- **Warm Beige:** The foundational neutral used for section containers to prevent the interface from feeling "stark white."
- **Soft Gold:** Reserved for borders, thin icons, or specific "Premium" badges; never used as a solid fill for large areas.

Strictly avoid fuchsia, neon, or yellow-based creams. All shadows and dividers should use a desaturated version of the text color at very low opacity (3-5%) to maintain the "warmth" without appearing muddy.

## Typography

The typography strategy pairs the editorial authority of **Playfair Display** with the approachable modernism of **Plus Jakarta Sans**. 

- **Headlines:** Use Playfair Display for all emotional hooks and service names. It should feel rhythmic and elegant. Use tighter letter spacing for large display sizes.
- **Body Text:** Plus Jakarta Sans provides high legibility for service descriptions and pricing. Use a generous line height (1.5 - 1.6) to maintain an airy feel.
- **Labels:** Use uppercase Jakarta Sans with tracking (letter spacing) for small headers, breadcrumbs, or category tags to create a "boutique" look.

## Layout & Spacing

This design system utilizes a **Fluid Grid** with intentional "breathing room." 

- **Desktop:** A 12-column grid with wide 80px - 120px vertical section gaps to emphasize exclusivity.
- **Mobile:** A single-column flow with 24px horizontal margins. 
- **Rhythm:** All spacing must be a multiple of 8px. Use larger padding inside containers (32px+) to ensure content doesn't feel cramped, mirroring the physical space of a luxury salon.
- **Alignment:** Content is primarily left-aligned or center-aligned for a symmetrical, balanced feel.

## Elevation & Depth

To maintain the "Boutique Minimalist" aesthetic, we avoid heavy shadows. Depth is achieved through:
- **Tonal Layering:** Using the Warm Beige (#F9F7F2) against a White (#FFFFFF) background to define cards and sections.
- **Soft Ambient Shadows:** When elevation is required (e.g., a floating "Book Now" button), use a very diffused shadow: `box-shadow: 0 10px 30px rgba(112, 104, 98, 0.08)`.
- **Subtle Gold Borders:** 1px solid borders in Soft Gold (#D4AF37) are used to define high-priority interactive elements or input fields.

## Shapes

The shape language is organic and "pill-shaped," avoiding sharp angles to maintain a friendly and caring tone. 

- **Buttons & Chips:** Always fully rounded (pill-shaped).
- **Cards & Image Containers:** Use the `rounded-xl` (3rem) setting for a soft, modern look. 
- **Form Inputs:** Softly rounded corners (1rem) to balance utility with the brand aesthetic.
- **Imagery:** Product and service photography should feature soft-focus edges or be contained within rounded-rectangles.

## Components

- **Buttons:** Primary buttons are large and high-contrast, using the Dark Neutral text color (#2D2926) with white text, or Primary Pink with Dark Neutral text. They must have a minimum height of 56px on mobile for ease of use.
- **Inputs:** Clean, 1px gold or beige bordered fields with floating labels in Plus Jakarta Sans. No heavy fills.
- **Cards:** White surfaces on Beige backgrounds. Cards should have no border, but a very soft, large-radius shadow to suggest they are "resting" on the surface.
- **Service Lists:** Use elegant serif headlines for service names, with price points in a slightly lighter weight Jakarta Sans. Use thin beige dividers between items.
- **Booking Bar:** A persistent, mobile-optimized bottom bar with a single, high-contrast "Book Appointment" pill button.
- **Chips/Tags:** Used for "Best Seller" or "New Service." These use the Lavender background with slightly darker purple text, always pill-shaped.