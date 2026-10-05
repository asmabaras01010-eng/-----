---
name: Éclat Beauté
colors:
  surface: '#fff8f8'
  surface-dim: '#dfd8d9'
  surface-bright: '#fff8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f9f2f3'
  surface-container: '#f4eced'
  surface-container-high: '#eee6e7'
  surface-container-highest: '#e8e1e2'
  on-surface: '#1e1b1c'
  on-surface-variant: '#524345'
  inverse-surface: '#332f30'
  inverse-on-surface: '#f7eff0'
  outline: '#857374'
  outline-variant: '#d7c1c3'
  surface-tint: '#8c4b55'
  primary: '#8a4853'
  on-primary: '#ffffff'
  primary-container: '#a6606b'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb2bc'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#625a55'
  on-tertiary: '#ffffff'
  tertiary-container: '#7c736d'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9dd'
  primary-fixed-dim: '#ffb2bc'
  on-primary-fixed: '#3a0915'
  on-primary-fixed-variant: '#70343e'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ece0d9'
  tertiary-fixed-dim: '#cfc4be'
  on-tertiary-fixed: '#201a16'
  on-tertiary-fixed-variant: '#4d4540'
  background: '#fff8f8'
  on-background: '#1e1b1c'
  surface-variant: '#e8e1e2'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 52px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Noto Serif
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
  title-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  title-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style

This design system embodies high-end sensorial luxury, warmth, and modern Middle Eastern elegance. It merges tactile soft-luxe aesthetics with pristine digital craft. The experience is Arabic-first (RTL native), celebrating calligraphic rhythm and modern high-fashion editorial layouts.

### Visual Style
- **Aesthetic Movement:** Warm Luxe Glassmorphism & Soft Tonalism.
- **Key Characteristics:** Generous breathing room, velvety card surfaces, luminous warm highlights, translucent floating navigation bars with high-definition backdrop blurs, and delicate champagne accents.
- **Emotional Response:** Indulgence, bespoke care, trust, prestige, and effortless serenity.

## Colors

The palette balances luminous skin-like undertones with confident, high-contrast dark charcoal for utmost legibility.

- **Primary (`#B76E79` - Dusty Rose Gold):** Anchors primary call-to-actions, cart badges, active toggles, and hero highlights.
- **Secondary (`#D4AF37` - Champagne Metallic):** Reserved for VIP badges, star ratings, premium seals, and delicate border illuminations.
- **Tertiary (`#F4E8E1` - Soft Nude Alabaster):** Applied across secondary button fills, chip containers, subtle card strokes, and neutral backgrounds.
- **Neutral (`#211E1F` - Deep Obsidian Charcoal):** Used for headlines, critical checkout balances, and dense body text, providing accessible contrast against nude and blush backgrounds without the harshness of pure black.
- **Canvas & Surface Tones:**
  - Base canvas: `#FAF6F2` (Warm Cashmere).
  - Surface cards: `#FFFFFF` with warm undertones.
  - Muted text: `#6E6663` (Smoked Taupe).
  - Validation: Positive `#3D7858` (Earthy Olive Sage), Destructive `#B03A48` (Crimson Rose).

## Typography

The type system pairs **Noto Serif** (refined, classical editorial voice tailored for high-fashion Arabic and Latin editorial headlines) with **Be Vietnam Pro** (exceptionally legible, geometric, open counter-forms for mobile screens, prices, product descriptions, and dense navigational labels).

### RTL & Arabic Typography Rules
- Line heights in Arabic are boosted by ~15% relative to standard Latin systems to accommodate high ascenders and cascading diacritics without clipping.
- Do not apply tracking/letter-spacing adjustments to Arabic scripts, as it degrades glyph connectivity; restrict letter-spacing strictly to Latin alphanumeric labels, SKUs, and prices.
- Numbers default to Eastern Arabic numerals (`٠-٩`) or localized Western Arabic (`0-9`) based on user locale selection while retaining tabular figure alignments in checkout summaries.

## Layout & Spacing

The layout is built for touch-first handheld interaction, organized on an 8pt base grid with a 4pt baseline subdivision.

### Grid & Viewport Handling
- **Mobile Handheld (360px - 480px):** 4-column fluid layout with `margin-mobile` (16px) margins and `gutter-mobile` (12px) gutters. Essential checkout CTAs are pinned to bottom safe areas using fixed glass anchors.
- **Tablet / Large Mobile Foldable (481px - 840px):** 8-column layout with 24px margins, introducing two-column product discovery and split checkout layouts.
- **RTL Fluidity:** Layout matrices automatically mirror: leading margins map to the visual right, carousels drag natural right-to-left, and navigation back chevrons point eastward (`→`).

## Elevation & Depth

Visual hierarchy uses warm, diffuse ambient drop-shadows infused with blush undertones rather than cold grays, paired with frosted glassmorphic navigation panels.

### Elevation Levels
- **Level 0 (Flat / Canvas):** Surface color `#FAF6F2`. No shadow.
- **Level 1 (Product Cards & Micro Panels):** Surface `#FFFFFF`. Shadow: `0 4px 20px -2px rgba(183, 110, 121, 0.08)`. Border: 1px solid `rgba(244, 232, 225, 0.6)`.
- **Level 2 (Floating Cart Bar & Dropdowns):** Surface `rgba(255, 255, 255, 0.88)` with `backdrop-filter: blur(16px)`. Shadow: `0 8px 30px -4px rgba(33, 30, 31, 0.08)`.
- **Level 3 (Modal Sheets, Bottom Checkout Sheets):** Surface `#FFFFFF`. Shadow: `0 -12px 40px -4px rgba(33, 30, 31, 0.12)`.

## Shapes

The design system employs a soft-luxe organic silhouette language that reflects cosmetic compacts, serum droplets, and sculpted glass jars.

- **Base Radius (0.5rem / 8px):** Small badges, notification counts, and inner stepper controls.
- **Large Radius (1rem / 16px):** Form fields, input blocks, compact list items, and standard catalog product tiles.
- **Extra Large Radius (1.5rem / 24px):** Hero promotional cards, imagery containers, and sliding bottom checkout drawers.
- **Full Pill (`9999px`):** CTAs, search inputs, luxury ingredient pills, and category filter chips.

## Components

### Buttons
- **Primary:** Full pill (`roundedness: 3` equivalent), height 52px for optimal touch target. Background is primary dusty rose (`#B76E79`) with crisp white typography (`label-lg`). Includes a soft directional gradient `linear-gradient(135deg, #C27D88 0%, #B76E79 100%)`.
- **Secondary / Ghost Luxe:** Border of 1px solid `#D4AF37` (Champagne Gold), transparent or `#F4E8E1` tint fill, text in `#211E1F`.

### Cards & Catalog Tiles
- Product cards feature a 16px to 20px radius, seamless subtle borders (`#F4E8E1`), and generous internal padding (`space-md`).
- Integrated wishlist heart button positioned at top visual left (RTL equivalent of the trail position), suspended in a circular frosted glass puck (`backdrop-filter: blur(8px)`).
- Visual hierarchy: Clean studio product photograph on pale warm tint, followed by brand subtitle, Arabic product title (`title-md`), shade/size indicator chip, and price anchored in deep charcoal with optional rose-gold discount tagging.

### Chips & Filter Pills
- Fully rounded pills (`height: 36px`), filled with `#FAF6F2` in unselected state and `#211E1F` with pure white text or `#B76E79` with rose tint when selected.
- Fragrance/shade swatch chips feature a circular inner preview dot (e.g., lipstick shade tone) accompanied by typography.

### Input Fields & Checkout Controls
- Floating or clear persistent top labels (`label-md`) aligned to the right.
- Input container height 52px, radius 16px, background `#FFFFFF`, border 1px solid `rgba(183, 110, 121, 0.24)`. Focus state intensifies to 1.5px solid `#B76E79` with a soft glow ring (`rgba(183, 110, 121, 0.15)`).
- Error messages sit below the field aligned right in `#B03A48`.

### Checkboxes & Radio Selectors
- Radios and checkmarks are custom-styled with a 22px diameter.
- Checked state fills with `#B76E79` containing a delicate white check glyph or inner champagne gold bullseye for payment option selectors (Apple Pay, Mada, Credit Card, Tabby/Tamara split payments).

### Mobile Bottom Sheets (Checkout & Cart Drawer)
- Top corners curved at 24px radius with an ambient drag handle indicator (`40px × 4px`, `#E5D9D2`).
- Fixed persistent bottom bar providing order subtotal, localized VAT note, and the prominent primary action button.