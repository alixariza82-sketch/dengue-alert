---
name: Marine Professionalism
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#3c4947'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#6c7a77'
  outline-variant: '#bbcac6'
  surface-tint: '#006a60'
  primary: '#006a60'
  on-primary: '#ffffff'
  primary-container: '#19b5a5'
  on-primary-container: '#00403a'
  inverse-primary: '#54dbca'
  secondary: '#1a60a3'
  on-secondary: '#ffffff'
  secondary-container: '#7db6ff'
  on-secondary-container: '#00477f'
  tertiary: '#765b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#c79c16'
  on-tertiary-container: '#483600'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#74f8e6'
  primary-fixed-dim: '#54dbca'
  on-primary-fixed: '#00201c'
  on-primary-fixed-variant: '#005048'
  secondary-fixed: '#d3e4ff'
  secondary-fixed-dim: '#a2c9ff'
  on-secondary-fixed: '#001c38'
  on-secondary-fixed-variant: '#004882'
  tertiary-fixed: '#ffdf94'
  tertiary-fixed-dim: '#efc13e'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#594400'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Open Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Open Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 14px
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
  lg: 40px
  xl: 64px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

This design system is built to evoke a sense of energetic reliability and clear communication. It targets sectors that require both a modern, high-tech edge and a human-centric, accessible approach—such as community education, environmental technology, or civic services. 

The visual style is **Corporate / Modern** with a focus on high-legibility and vibrant accents. It utilizes generous white space to create a clean, organized environment where information is prioritized. The aesthetic relies on the interplay between deep, trustworthy foundations and bright, optimistic highlights to keep the user engaged and focused.

## Colors

The palette is anchored by **Deep Blue (#145DA0)**, used for primary navigation, footers, and foundational elements to establish authority and trust. **Turquoise (#19B5A5)** serves as the primary action color, used for buttons, interactive states, and success indicators, providing a fresh and modern energy.

**Caribbean Yellow (#F4C542)** is reserved for high-impact accents, warnings, or specific highlights to draw attention without overwhelming the UI. The background remains a soft, neutral off-white to reduce eye strain, while text defaults to a deep charcoal to maintain AAA accessibility standards against the vibrant primary colors.

## Typography

This design system employs a dual-font strategy to balance character with utility. **Montserrat** is the display typeface, utilized for all headings, logos, and high-level titles. Its geometric structure provides a confident and modern "voice" to the brand.

**Open Sans** is used for all body text, user interface elements, labels, and informative content. It was selected for its exceptional legibility across various screen resolutions and its friendly, humanist character. 

For accessibility, ensure that body text never falls below 16px for primary reading content. Use weight increases (Semi-Bold/Bold) in Open Sans to indicate hierarchy in UI labels rather than changing the font family.

## Layout & Spacing

The layout is built on a **12-column fluid grid** for desktop and a **4-column grid** for mobile. A consistent 8px base unit (the "Step") governs all padding and margins to ensure visual harmony.

- **Desktop (1440px+):** 12 columns with 24px gutters and 48px side margins.
- **Tablet (768px - 1439px):** 8 columns with 20px gutters and 32px side margins.
- **Mobile (Up to 767px):** 4 columns with 16px gutters and 16px side margins.

Content should follow a logical vertical rhythm, using larger spacing (64px+) to separate major sections and smaller spacing (12px-24px) for related items within cards or lists.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and subtle **Ambient Shadows**. This design system avoids heavy skueomorphism, opting instead for a "layered paper" effect.

1.  **Level 0 (Surface):** The default background color.
2.  **Level 1 (Cards/Containers):** White background with a 1px border (#E9ECEF) or a very soft, diffused shadow (0px 4px 12px rgba(20, 93, 160, 0.08)).
3.  **Level 2 (Popovers/Modals):** Floating elements with a more defined shadow to indicate they are closer to the user (0px 8px 24px rgba(0, 0, 0, 0.12)).

Interactive elements like buttons should use a subtle elevation lift on hover rather than a color change alone.

## Shapes

The design system uses a **Rounded (2)** shape language. This softens the geometric nature of the Montserrat typeface and makes the UI feel approachable and friendly.

- **Standard Elements:** 0.5rem (8px) for buttons, input fields, and small cards.
- **Large Containers:** 1rem (16px) for modals and primary content sections.
- **Micro-Elements:** 4px for checkboxes or tags.

Pill-shaped (fully rounded) containers should be used exclusively for status "Chips" or "Badges" to distinguish them from actionable buttons.

## Components

### Buttons
Primary buttons use a Turquoise (#19B5A5) background with white text (Open Sans Bold). Secondary buttons use a Deep Blue (#145DA0) outline with Deep Blue text. 

### Input Fields
Inputs utilize a 1px neutral border with 8px rounded corners. On focus, the border transitions to Deep Blue with a soft 2px Turquoise glow to indicate activity. Labels are always placed above the field in Open Sans (Label-md).

### Cards
Cards are white with a Level 1 shadow. Headings inside cards must use Montserrat (Headline-sm), while descriptions use Open Sans (Body-sm).

### Chips & Tags
Used for categorization. These are pill-shaped with light tints of the primary colors (e.g., 10% opacity Turquoise background with 100% Turquoise text) to maintain high legibility without distracting from primary actions.

### Lists
Lists use generous vertical padding (12px-16px per item) with a 1px separator line in a light neutral gray. Icons used within lists should be monochromatic Deep Blue to maintain a professional look.