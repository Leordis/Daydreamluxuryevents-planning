---
name: Daydream Luxury Events
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
  on-surface-variant: '#484740'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efea'
  outline: '#79776f'
  outline-variant: '#c9c6bd'
  surface-tint: '#605e5b'
  primary: '#605e5b'
  on-primary: '#ffffff'
  primary-container: '#f9f5f0'
  on-primary-container: '#72706c'
  inverse-primary: '#c9c6c1'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#685c56'
  on-tertiary: '#ffffff'
  tertiary-container: '#fff3ef'
  on-tertiary-container: '#7a6d68'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e6e2dd'
  primary-fixed-dim: '#c9c6c1'
  on-primary-fixed: '#1c1c19'
  on-primary-fixed-variant: '#484743'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#f0dfd8'
  tertiary-fixed-dim: '#d3c3bc'
  on-tertiary-fixed: '#221a16'
  on-tertiary-fixed-variant: '#50443f'
  background: '#fff8f5'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '300'
    lineHeight: '1.8'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '300'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.15em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max-width: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style
The design system is rooted in the high-end Florida wedding market, evoking the sensation of a coastal breeze and the tactile quality of a premium linen invitation. The brand personality is poised, romantic, and meticulously curated, targeting a discerning clientele that values exclusivity and effortless elegance.

The design style is **Editorial Minimalism** mixed with **Soft Glassmorphism**. It utilizes expansive white space (breathing room) to allow high-resolution event photography to serve as the primary visual anchor. Transitions should feel fluid and rhythmic, mimicking the slow turn of a luxury magazine page. The emotional response is one of calm, aspiration, and trust.

## Colors
The palette is a sophisticated blend of organic neutrals and metallic warmth. 
- **Ivory (#F9F5F0):** The primary canvas color, used for backgrounds to create a softer, more premium feel than pure white.
- **Gold (#D4AF37):** Used sparingly for interactive highlights, delicate borders, and iconography to signal luxury.
- **Blush (#E8D7D0) & Sage (#B2BCA3):** Secondary tones used for subtle background washes, category tags, or decorative elements to provide a natural, floral-inspired depth.
- **Ink (#2D2926):** A soft off-black used for typography to maintain high legibility without the harshness of true black.

## Typography
The typographic hierarchy leans heavily on the contrast between the evocative, high-contrast strokes of **Playfair Display** and the clean, airy geometry of **Montserrat**.

- **Headlines:** Use Playfair Display in "Italic" for emphasized words within a sentence to enhance the romantic, editorial feel. 
- **Body:** Use the 300 (Light) weight of Montserrat for all long-form text to maintain a modern, ethereal quality. Increase line height significantly to promote readability and a sense of "ease."
- **Labels:** Use uppercase Montserrat with generous letter spacing for navigation, small headings, and button labels to create a structured, architectural feel.

## Layout & Spacing
The layout follows a **Fixed Central Grid** on desktop and a **Fluid Single Column** on mobile. 

- **Breathing Room:** Utilize aggressive vertical spacing (Section Gaps) between content blocks to prevent the UI from feeling "crowded." 
- **Asymmetry:** Occasionally break the grid with images that offset slightly from the text to mimic high-end magazine layouts.
- **Desktop:** A 12-column grid with wide margins (64px+) to create a focused, storytelling experience in the center of the screen.
- **Mobile:** Transition to a 4-column grid with 20px margins, prioritizing large-scale imagery and centered typography.

## Elevation & Depth
Depth is achieved through **Tonal Layering** and **Soft Ambient Shadows**. 

Avoid heavy dropshadows. Instead, use "Soft-Light" shadows with a large blur radius (30px+) and very low opacity (5-8%) tinted with the primary Gold or Blush hex codes. This creates a "levitating" effect rather than a "heavy" one. 

For overlays (modals or dropdowns), use a **Backdrop Blur** (10px - 20px) with a semi-transparent Ivory fill. This maintains the "airy" feel while providing functional separation. Delicate 1px gold borders should be used to define containers on light backgrounds.

## Shapes
The shape language is **Soft and Sophisticated**. 

The design system uses a subtle 4px (0.25rem) corner radius for most functional elements like buttons and input fields, providing a "tailored" look that is neither sharp nor overly bubbly. 

For decorative elements, such as featured image frames or "book-now" buttons, use **Pill-shapes** or **Circular** crops to introduce feminine, flowing curves that contrast with the structured grid.

## Components
- **Buttons:** Primary buttons are outlined in 1px Gold or solid Ivory with a subtle shadow. Text is always uppercase Montserrat with 0.15em spacing. Hover states should involve a soft color wash or a slight lift.
- **Inputs:** Minimalist bottom-border only or very light 1px frames. Focus states should transition the border color to Gold.
- **Cards:** Use "Floating Cards" for testimonials or services—Ivory backgrounds on a slightly darker Ivory/Blush section, using the soft ambient shadows defined in Elevation.
- **Chips/Tags:** Used for "Event Types" (e.g., *Destination*, *Black Tie*). These should be pill-shaped with a Sage or Blush background and dark text.
- **Image Containers:** Use a "Signature Frame"—a 1px Gold border that sits 12px outside of the image itself to create an editorial, framed look.
- **Navigation:** A centered, minimalist top-bar. On scroll, it should adopt the glassmorphic backdrop blur effect.