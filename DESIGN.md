---
name: Culinary Heritage
colors:
  surface: '#fff8f4'
  surface-dim: '#e2d8d1'
  surface-bright: '#fff8f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fcf2eb'
  surface-container: '#f6ece5'
  surface-container-high: '#f0e6df'
  surface-container-highest: '#eae1da'
  on-surface: '#1f1b17'
  on-surface-variant: '#50443f'
  inverse-surface: '#352f2b'
  inverse-on-surface: '#f9efe8'
  outline: '#82746e'
  outline-variant: '#d4c3bc'
  surface-tint: '#795745'
  primary: '#371e0f'
  on-primary: '#ffffff'
  primary-container: '#503323'
  on-primary-container: '#c49b86'
  inverse-primary: '#eabda7'
  secondary: '#645d57'
  on-secondary: '#ffffff'
  secondary-container: '#ebe1d8'
  on-secondary-container: '#6b635c'
  tertiary: '#08282b'
  on-tertiary: '#ffffff'
  tertiary-container: '#213e41'
  on-tertiary-container: '#8ba9ac'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbca'
  primary-fixed-dim: '#eabda7'
  on-primary-fixed: '#2d1508'
  on-primary-fixed-variant: '#5f402f'
  secondary-fixed: '#ebe1d8'
  secondary-fixed-dim: '#cfc5bd'
  on-secondary-fixed: '#201b16'
  on-secondary-fixed-variant: '#4c4640'
  tertiary-fixed: '#c9e8ec'
  tertiary-fixed-dim: '#adcccf'
  on-tertiary-fixed: '#002022'
  on-tertiary-fixed-variant: '#2f4b4e'
  background: '#fff8f4'
  on-background: '#1f1b17'
  surface-variant: '#eae1da'
  espresso: '#211c17'
  terracotta: '#503323'
  parchment: '#f4eae3'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  headline-md:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '300'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.15em
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 24px
---

## Brand & Style

This design system embodies the essence of high-end gastronomy—precision, warmth, and timelessness. The visual identity is built for a professional chef whose brand is rooted in "Cuisiner l’essentiel" (Cooking the essential). 

The style is **Minimalist and Editorial**, characterized by expansive white space, a warm earth-toned palette, and classical serif typography. It avoids unnecessary decoration, allowing high-fidelity photography of ingredients and plated dishes to serve as the primary visual texture. The emotional response is one of quiet luxury, authenticity, and artisanal mastery.

## Colors

The palette is derived from natural, culinary elements: charred wood, rich sauces, and organic linens. 

- **Parchment (#f4eae3):** Used as the primary background color to provide a softer, more sophisticated feel than pure white. It mimics the texture of a high-quality menu or chef's stationary.
- **Terracotta (#503323):** The primary brand color, used for headers and key brand elements. It conveys warmth and groundedness.
- **Espresso (#211c17):** A near-black neutral used for body text and high-contrast UI elements to ensure legibility while maintaining the warm tonal profile.

## Typography

The typography system relies on the contrast between the classic, literary feel of **EB Garamond** (as a high-end alternative to Cormorant Garamond) and the clean, modern functionality of **Montserrat**.

- **Serif (EB Garamond):** Reserved for headlines, quotes, and brand statements. It should be set with generous leading and occasionally negative letter-spacing for large display titles to emphasize its elegant strokes.
- **Sans-Serif (Montserrat):** Used for body copy, navigation, and functional labels. Use lighter weights (300/400) to maintain the minimalist aesthetic. 
- **Label-caps:** Specifically designed for "Univers Visuel" or sub-navigation headers, utilizing wide letter-spacing to create an airy, architectural feel.

## Layout & Spacing

This design system uses a **Fixed Grid** philosophy for desktop to maintain the feel of a printed editorial piece, transitioning to a fluid layout for mobile devices.

- **Desktop:** 12-column grid with a 1200px max-width. Margins are intentionally wide (64px+) to create a "frame" around the content.
- **Rhythm:** Use an 8px base unit. Vertical spacing between sections should be aggressive (e.g., 128px or 160px) to give the content "room to breathe."
- **Asymmetry:** Occasionally break the grid with images that bleed to the edge of the screen or offset text blocks to create a contemporary, curated look.

## Elevation & Depth

To maintain the high-end minimalist aesthetic, this design system avoids traditional drop shadows and heavy elevation.

- **Tonal Layering:** Depth is created through subtle shifts in background color (e.g., using a slightly darker version of Parchment for secondary sections).
- **Hairline Dividers:** Use 1px solid lines in the `primary_color` at low opacity (10-20%) to separate content sections without adding visual weight.
- **Flat Surfaces:** Components like cards should appear to be flush with the surface, distinguished only by a change in background tint or a fine border.

## Shapes

The shape language is strictly **Sharp (0)**. 

Rectangular forms, right angles, and crisp edges reflect the precision of a chef's knife and the formal structure of fine dining. Circular elements should only be used for specific brand marks (like the MB monogram) or for functional elements like radio buttons, but never for cards, containers, or primary buttons.

## Components

- **Buttons:** Use "Ghost" or "Solid" styles. Solid buttons should use the `primary_color` with `label-caps` text in the `neutral_color`. Ghost buttons use a 1px `primary_color` border. No rounded corners.
- **Cards:** Cards should have no background or shadow by default. They are defined by their alignment and the use of a hairline top-border to separate them in a list.
- **Inputs:** Simple bottom-border only (1px solid Espresso). Labels should use the `label-caps` style positioned above the field.
- **Navigation:** Top-tier navigation should be centered, utilizing `label-caps` with subtle hover states (opacity change or a simple 1px underline).
- **Images:** Always high-resolution. Use a "reveal on scroll" animation to enhance the premium feel.