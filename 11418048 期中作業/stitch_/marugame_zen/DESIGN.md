---
name: Marugame Zen
colors:
  surface: '#fff8f5'
  surface-dim: '#e4d7d2'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fef1eb'
  surface-container: '#f9ebe5'
  surface-container-high: '#f3e6e0'
  surface-container-highest: '#ede0da'
  on-surface: '#211a17'
  on-surface-variant: '#524345'
  inverse-surface: '#362f2b'
  inverse-on-surface: '#fbeee8'
  outline: '#847375'
  outline-variant: '#d6c2c4'
  surface-tint: '#894d59'
  primary: '#894d59'
  on-primary: '#ffffff'
  primary-container: '#f2a7b5'
  on-primary-container: '#723a46'
  inverse-primary: '#feb2c0'
  secondary: '#99461d'
  on-secondary: '#ffffff'
  secondary-container: '#fe9566'
  on-secondary-container: '#762c03'
  tertiary: '#615e57'
  on-tertiary: '#ffffff'
  tertiary-container: '#c0bbb2'
  on-tertiary-container: '#4e4b44'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9df'
  primary-fixed-dim: '#feb2c0'
  on-primary-fixed: '#370b18'
  on-primary-fixed-variant: '#6d3642'
  secondary-fixed: '#ffdbcd'
  secondary-fixed-dim: '#ffb596'
  on-secondary-fixed: '#360f00'
  on-secondary-fixed-variant: '#7a3006'
  tertiary-fixed: '#e7e2d8'
  tertiary-fixed-dim: '#cbc6bd'
  on-tertiary-fixed: '#1d1b16'
  on-tertiary-fixed-variant: '#494740'
  background: '#fff8f5'
  on-background: '#211a17'
  surface-variant: '#ede0da'
typography:
  headline-lg:
    fontFamily: Noto Serif TC
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Serif TC
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Noto Serif TC
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
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
    fontFamily: Be Vietnam Pro
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
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

The design system is centered on the concept of "Omotenashi" (Japanese hospitality) and the steam-filled warmth of an udon kitchen. It seeks to evoke a sense of comfort, artisan craft, and culinary delight. The target audience includes food enthusiasts, families, and busy professionals seeking a moment of authentic tranquility.

The style is **Modern Tactile**, blending clean minimalist layouts with subtle organic textures reminiscent of washi paper and steamed flour. It avoids the clinical coldness of modern tech by using soft transitions, warm lighting effects, and a composition that mirrors the balanced arrangement of a traditional Japanese meal.

## Colors

The palette is inspired by the delicate pink of cherry blossoms (Sakura) and the toasted warmth of tempura. 

- **Primary (Sakura Pink):** Used for key brand moments and soft highlights.
- **Secondary (Miso Orange):** Used for call-to-action elements to stimulate appetite and create energy.
- **Tertiary (Cream/Flour):** The primary background color, providing a softer, more organic feel than pure white.
- **Neutral (Charcoal Wood):** Used for typography to ensure high legibility while maintaining a soft, natural contrast compared to pure black.

## Typography

This design system utilizes a harmonious mix of serif and sans-serif typefaces to balance tradition and modernity. 

- **Headlines:** Use Noto Serif TC for all Traditional Chinese headings. The serif strokes reflect the elegance of Japanese calligraphy and the artisanal nature of handmade udon.
- **Body:** Plus Jakarta Sans provides a friendly, rounded geometric feel for English text and secondary descriptions, ensuring high readability on mobile devices.
- **Labels:** Be Vietnam Pro is used for utilitarian micro-copy and navigation, offering a contemporary, approachable tone.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop, transitioning to a fluid single-column model for mobile. It uses a 12-column grid system with generous margins to create "Ma" (negative space), which is essential in Japanese aesthetics to allow the content to breathe.

Spacing follows a 4px base unit. Component containers should prioritize internal padding over external margins to maintain a sense of structural integrity and "fullness," similar to a well-presented bowl of noodles.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** and **Ambient Shadows**. Instead of harsh dropshadows, this design system uses soft, colored glows (tinted with the secondary orange or primary pink) to suggest depth.

- **Level 1 (Surface):** Cream background.
- **Level 2 (Cards):** White surfaces with a very soft, diffused pink-tinted shadow (Blur: 20px, Opacity: 5%).
- **Level 3 (Overlays/Modals):** Slight backdrop blur (8px) combined with a delicate inner border to simulate a shoji screen effect.

## Shapes

The shape language is defined by **Rounded** geometry. Sharp corners are avoided to maintain the "friendly and appetizing" atmosphere. 

Corners follow a consistent radius to mimic the soft curves of udon noodles and ceramic bowls. Card elements and primary buttons use a 0.5rem base radius, while smaller tags and chips may use pill-shaped containers to suggest a more organic, handcrafted feel.

## Components

- **Buttons:** Primary buttons should use the Secondary (Miso Orange) color with white text for maximum visibility. They should feature a subtle hover state that increases the saturation.
- **Cards:** Used for menu items. They should feature high-quality photography, a white background, and the Level 2 shadow depth. Headlines within cards should be Noto Serif TC.
- **Chips/Tags:** Used for dietary labels (e.g., "Vegetarian") or seasonal specials. These should be pill-shaped with light pink backgrounds and dark brown text.
- **Input Fields:** Soft cream backgrounds with a thin 1px border in a muted pink. On focus, the border should thicken and brighten to the primary pink.
- **Navigation:** Top-tier navigation should be clean and spacious, using the Label-MD style with generous horizontal tracking.
- **Specialty Component (The "Noren" Header):** A unique header style for section titles that mimics the appearance of a Japanese shop curtain (Noren), using a vertical text orientation for short Traditional Chinese phrases.