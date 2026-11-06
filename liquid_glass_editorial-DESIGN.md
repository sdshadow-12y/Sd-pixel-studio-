---
name: Liquid Glass Editorial
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#3f4850'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#707881'
  outline-variant: '#bfc7d2'
  surface-tint: '#006398'
  primary: '#006194'
  on-primary: '#ffffff'
  primary-container: '#007bb9'
  on-primary-container: '#fdfcff'
  inverse-primary: '#93ccff'
  secondary: '#a43073'
  on-secondary: '#ffffff'
  secondary-container: '#fc79bd'
  on-secondary-container: '#76014e'
  tertiary: '#006387'
  on-tertiary: '#ffffff'
  tertiary-container: '#007da9'
  on-tertiary-container: '#fcfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cce5ff'
  primary-fixed-dim: '#93ccff'
  on-primary-fixed: '#001d31'
  on-primary-fixed-variant: '#004b73'
  secondary-fixed: '#ffd8e7'
  secondary-fixed-dim: '#ffafd3'
  on-secondary-fixed: '#3d0026'
  on-secondary-fixed-variant: '#85145a'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-xl:
    fontFamily: Syne
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 78px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 46px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 54px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 2rem
  margin-mobile: 1.25rem
  margin-desktop: 4rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

This design system establishes an ethereal, hyper-tactile visual identity tailored for an elite digital craft studio. The aesthetic bridges high-end editorial curation with cutting-edge optical physics: **Liquid Glassmorphism**.

The visual language evokes the sensation of polished, ultra-pure crystalline glass floating over soft, diffused ambient light pools. Light interacts naturally with surface boundaries through directional specular reflections, subtle prismatic edge chromatic aberration, and multi-layered backdrop filtration.

### Emotional Signature
- **Pristine & Weightless:** Interfaces float naturally with optical physics, depth, and spatial fluidity.
- **Masterful Precision:** Razor-sharp typography and obsidian contrast anchored within soft atmospheric diffusion.
- **Tactile Refraction:** Interactions reward users with fluid distortions, luminous rim highlights, and ambient light dispersal.

## Colors

The palette balances optical clarity with soft ambient chromatic warmth. It employs high-contrast obsidian tones for core typographic accessibility laid against luminous, semi-translucent fluid surfaces.

### Surface Color Logic
- **Canvas Base:** Pristine fluid tint `#F8FAFC`, accented by stationary or interactive ambient radial gradients using Sky Mist (`#E0F2FE` at 40% blur radius) and Rose Quartz (`#FDF2F8` at 35% blur radius).
- **Glass Panel Surface:** Semi-transparent crisp white (`rgba(255, 255, 255, 0.65)` to `rgba(255, 255, 255, 0.82)`), adapting dynamically depending on background luminance.
- **Glass Specular Border:** Refractive rim edge highlight `rgba(255, 255, 255, 0.65)` on upper/left vectors transitioning to `rgba(255, 255, 255, 0.15)` on lower/right vectors.

### Chromatic Accents
- **Primary Celestial Cyan (`#0284C7` / `#38BDF8`):** Directs active focal states, key calls-to-action, and core navigation indicators.
- **Prismatic Rose (`#F472B6` / `#FCE7F3`):** Infuses secondary interactions, chromatic glass refraction glows, and creative portfolio tags.
- **Text & Contrast Hierarchy:** Rich Obsidian (`#0F172A`) for bold titles and primary body copy, supplemented by Muted Slate (`#475569`) for metadata and micro-labels.

## Typography

The typographic system creates an interplay between avant-garde editorial forms and functional legibility:

- **Syne (Display & Headlines):** Delivers sculptural presence, architectural tension, and an unmistakably bespoke studio feel. Used exclusively for brand statements, project titles, and hero narratives.
- **Plus Jakarta Sans (Body):** Offers clean geometric balance, open apertures, and warm ergonomics, counteracting visual fatigue over prolonged reading.
- **Inter (Labels & Micro-UI):** Utilized for structural metadata, tracking numbers, metrics, chips, and navigational systems, ensuring absolute precision across all screen densities.

## Layout & Spacing

The layout is built upon a fluid 12-column grid architecture designed to breathe with spacious editorial pacing. 

### Breakpoints & Adaptive Reflow
- **Mobile (< 768px):** 4 fluid columns, `margin-mobile` (1.25rem / 20px), gutters of 1rem. Modals, cards, and floating panels stretch edge-to-edge with continuous glass sheets.
- **Tablet (768px – 1024px):** 8 fluid columns, adaptive margins of 2rem. Grids reflow from stacked singles into paired dual-column galleries.
- **Desktop (> 1024px):** 12 fluid columns with maximum content container capped at 1440px. Section margins extend to `margin-desktop` (4rem / 64px), permitting vast airy intervals around hero copy and work displays.

### Spacing Principles
All spacing tokens govern spatial separation exclusively. Components float over wide spatial expanses (`space-xl` and `space-lg`) to allow background liquid refractions and subtle chromatic light gradients to drift visibly between glass surfaces.

## Elevation & Depth

Visual hierarchy does not rely on opaque stacking or harsh drop shadows. Instead, depth is rendered through multi-tier optical physics: progressive backdrop filtration, ambient luminous diffusion, and inner refractive highlights.

### Elevation Levels

1. **Level 0 (Fluid Canvas):** Pristine background `#F8FAFC` embedded with subtle radial light nodes (`#E0F2FE` and `#FDF2F8`) that create organic refraction opportunities for elements above.
2. **Level 1 (Docked Surfaces & Grid Panels):**
   - Background: `rgba(255, 255, 255, 0.55)`
   - Backdrop Filter: `blur(16px) saturate(180%)`
   - Border: 1px solid `rgba(255, 255, 255, 0.65)`
   - Shadow: `0 8px 32px -4px rgba(15, 23, 42, 0.04), 0 2px 8px -2px rgba(15, 23, 42, 0.02)`
3. **Level 2 (Interactive Floating Cards & Glass Navbars):**
   - Background: `rgba(255, 255, 255, 0.72)`
   - Backdrop Filter: `blur(20px) saturate(190%)`
   - Inset Highlight: `inset 0 1px 1px 0 rgba(255, 255, 255, 0.85)`
   - Border: 1px solid `rgba(255, 255, 255, 0.75)`
   - Shadow: `0 16px 40px -8px rgba(15, 23, 42, 0.06), 0 4px 16px -2px rgba(2, 132, 199, 0.04)`
4. **Level 3 (Modals, Overlays & Floating Action Badges):**
   - Background: `rgba(255, 255, 255, 0.85)`
   - Backdrop Filter: `blur(28px) saturate(200%)`
   - Inset Highlight: `inset 0 1.5px 2px 0 rgba(255, 255, 255, 1.0)`
   - Border: 1.5px solid `rgba(255, 255, 255, 0.9)`
   - Shadow: `0 24px 64px -12px rgba(15, 23, 42, 0.1), 0 0 24px 2px rgba(244, 114, 182, 0.08)`

## Shapes

The geometry mimics fluid surface tension—curved, frictionless, and soft to the touch. The roundedness setting anchors structural elements at `0.5rem` (8px), scaling to `1rem` (16px) for cards, and `1.5rem` (24px) for expansive hero panels.

Interactive badges, segmented tab bars, and floating filter controls use continuous, full-radius concentric capsules (pill forms) to accentuate their liquid aesthetic.

## Components

### Buttons
- **Primary Action (Liquid Glow):** Solid Obsidian (`#0F172A`) base or deep Sky Gradient (`linear-gradient(135deg, #0284C7, #38BDF8)`), crisp white text, rounded capsule shape (`border-radius: 9999px`). Features a subtle top rim gloss (`inset 0 1px 1px rgba(255, 255, 255, 0.35)`). Hover elevates through an outer cyan bloom (`0 10px 25px -4px rgba(2, 132, 199, 0.35)`).
- **Secondary Glass Button:** Translucent white (`rgba(255, 255, 255, 0.6)`), backdrop-blur of 16px, 1px perimeter border `rgba(255, 255, 255, 0.8)`. Hover transitions surface opacity to `0.85` with text shifting into `#0284C7`.

### Liquid Glass Cards
- Dual-layer composition: semi-opaque frosted glass body with 20px blur, contained by a light-reactive 1px gradient border (`linear-gradient(145deg, rgba(255, 255, 255, 0.9), rgba(255, 255, 255, 0.2))`).
- Internal media assets display subtle curved corners with smooth outer overflow masking. On hover, the inner visual scales up smoothly while card shadows gain a localized cyan/rose prismatic edge refraction.

### Pill Filter Tabs
- Segmented container styled as a floating frosted track with `blur(20px)`.
- Active segment glides beneath target labels using a pure white capsule plate (`#FFFFFF`) with soft directional ambient drop shadow (`0 4px 12px rgba(15, 23, 42, 0.06)`).
- Inactive tabs display muted slate typography (`#475569`), transforming to rich obsidian on hover.

### Frosted Search Bars & Input Fields
- Enclosed in continuous glass capsules (`border-radius: 9999px`) or rounded-lg containers with 16px blur.
- Background uses `rgba(255, 255, 255, 0.5)`.
- Focus state activates an outer cyan highlight ring (`box-shadow: 0 0 0 3px rgba(56, 189, 248, 0.3)`) and shifts the background fill to pristine frosted white (`rgba(255, 255, 255, 0.85)`).
- Placeholder copy rests at `#94A3B8`; active input text displays sharp obsidian `#0F172A`.

### Glowing Tags & Status Badges
- Compact pill tokens layered with delicate tint fills: Cyan Glass (`rgba(2, 132, 199, 0.08)` fill with `#0284C7` copy) and Rose Refraction (`rgba(244, 114, 182, 0.1)` fill with `#DB2777` copy).
- Rimmed with 1px semi-opaque colored glass borders and a live pulsing core dot.

### Floating Action Badges
- Free-floating glass discs (`backdrop-filter: blur(24px)`) containing iconography or micro-metrics.
- Bound to viewport safe corners or card boundaries via smooth floating hover transitions (`transform: translateY(-4px)`).