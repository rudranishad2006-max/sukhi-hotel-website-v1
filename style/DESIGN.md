---
name: Sukhi Hotel Design System
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
  on-surface-variant: '#444748'
  inverse-surface: '#303030'
  inverse-on-surface: '#f2f0f0'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1c19'
  on-tertiary-container: '#848480'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#e3e3de'
  tertiary-fixed-dim: '#c7c7c2'
  on-tertiary-fixed: '#1b1c19'
  on-tertiary-fixed-variant: '#464744'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 64px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 40px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 40px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
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
    lineHeight: '1.2'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 80px
  section-gap: 120px
---

## Brand & Style

The design system is anchored in the concept of "Modern Heritage." It strikes a balance between the high-end sophistication of a luxury lounge and the hospitable warmth inherent in Indian culture. The aesthetic is **Minimalist-Luxury**, utilizing expansive whitespace (ivory) to allow rich accents (gold) and deep foundations (charcoal) to feel intentional and curated.

The UI should evoke a sense of calm, exclusivity, and impeccable taste. Every interaction must feel deliberate, avoiding cluttered layouts in favor of an editorial approach that mirrors a fine-dining menu or a high-end travel journal.

## Colors

The palette is a classic "Noir et Or" (Black and Gold) refined for a contemporary Indian context.

*   **Charcoal (#1A1A1A):** Used for primary text, deep backgrounds, and high-contrast UI elements. It provides the "weight" of the brand.
*   **Warm Gold (#C5A059):** A muted, sophisticated metallic tone used sparingly for calls to action, highlights, and decorative accents. It should never feel gaudy.
*   **Ivory (#F9F8F3):** The primary background color. It is warmer and more inviting than pure white, providing a "paper-like" quality that feels premium.
*   **Slate Neutral (#4A4A4A):** Used for secondary text and subtle borders to maintain legibility without the harshness of pure black.

## Typography

This design system utilizes a classic serif/sans-serif pairing to communicate both tradition and modernity.

*   **Headlines:** **EB Garamond** brings a graceful, literary quality. Use it for titles, section headers, and quotes. It should be set with slightly tighter letter-spacing in larger sizes for a high-fashion look.
*   **Body:** **Plus Jakarta Sans** provides a soft, approachable contrast. Its modern proportions ensure high legibility for menu descriptions and long-form content.
*   **Labels & Navigation:** Use uppercase **Plus Jakarta Sans** with generous letter-spacing for small labels, buttons, and navigation items to evoke a sense of structured elegance.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to maintain a centered, editorial focus, while transitioning to a fluid model on mobile.

*   **Desktop:** 12-column grid with a maximum content width of 1280px. Use large margins (80px+) to create a "frame" around the content.
*   **Rhythm:** Vertical spacing is intentionally loose. Section gaps should be generous (120px+) to allow the design to breathe and emphasize the premium nature of the brand.
*   **Alignment:** Mix centered headings for major section intros with asymmetrical, left-aligned body text for a modern, dynamic feel.

## Elevation & Depth

To maintain a sophisticated aesthetic, this design system avoids heavy shadows in favor of **Tonal Layers** and **Low-Contrast Outlines**.

*   **Tiers:** Surfaces are defined by subtle shifts between Ivory (#F9F8F3) and a slightly darker "Stone" tint (#F2F0E9) for container backgrounds.
*   **Borders:** Use thin (1px) borders in a muted gold or soft charcoal at low opacity (15-20%) to define cards and inputs.
*   **Floating Elements:** Only high-priority elements like floating navigation bars or "Book a Table" modals should use shadows. These shadows must be "Ambient"—very long, diffused, and slightly tinted with the secondary gold color to feel like natural light hitting a surface.

## Shapes

The shape language is **Soft** and architectural. We avoid sharp, aggressive corners to keep the vibe inviting, but we also avoid hyper-rounded "bubbly" shapes to maintain a professional, high-end look.

*   **Primary Containers:** Use a 0.25rem (4px) radius for buttons and input fields.
*   **Image Frames:** Images should either be sharp (0px) for a strict editorial look or use a subtle 8px radius to feel softer.
*   **Accent Shapes:** Circular elements (like decorative badges or iconography backgrounds) provide a nice organic counterpoint to the structured grid.

## Components

### Buttons
*   **Primary:** Charcoal background with Ivory text. Rectangular with a 4px radius.
*   **Secondary:** Ghost style with a thin Gold border and Gold text. 
*   **Tertiary:** Gold text with a 1px underline, used for "Read More" or "View Menu" links.

### Input Fields
Inputs should be minimalist. A simple bottom border in Charcoal (2px) or a fully enclosed box with an Ivory background and a very faint Slate border. Focus states should transition the border color to Gold.

### Cards
Cards for menu items or room types should have no background or a very subtle "Stone" tint. Use large, high-quality photography as the hero element of the card. Typography inside cards should be centered for a premium look.

### Lists & Menus
For the restaurant menu, use a classic "dot leader" style (Item Name . . . . . Price) using EB Garamond for the item name and Plus Jakarta Sans for the description and price.

### Interactive Accents
Use gold for subtle micro-interactions, such as a thin line expanding under a navigation link on hover, or a soft gold glow behind a primary button when pressed.