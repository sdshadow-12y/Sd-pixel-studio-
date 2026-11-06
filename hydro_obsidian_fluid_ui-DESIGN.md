---
name: Hydro Obsidian Fluid UI
colors:
  surface: '#111417'
  surface-dim: '#111417'
  surface-bright: '#37393d'
  surface-container-lowest: '#0c0e12'
  surface-container-low: '#191c1f'
  surface-container: '#1d2023'
  surface-container-high: '#282a2e'
  surface-container-highest: '#323539'
  on-surface: '#e1e2e7'
  on-surface-variant: '#dbc2b1'
  inverse-surface: '#e1e2e7'
  inverse-on-surface: '#2e3134'
  outline: '#a38c7d'
  outline-variant: '#554336'
  surface-tint: '#ffb77d'
  primary: '#ffc08e'
  on-primary: '#4d2600'
  primary-container: '#ff9838'
  on-primary-container: '#6a3700'
  inverse-primary: '#914d00'
  secondary: '#7bd0ff'
  on-secondary: '#00354a'
  secondary-container: '#00a6e0'
  on-secondary-container: '#00374d'
  tertiary: '#ffbf9d'
  on-tertiary: '#542200'
  tertiary-container: '#ff9759'
  on-tertiary-container: '#723100'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdcc3'
  primary-fixed-dim: '#ffb77d'
  on-primary-fixed: '#2f1500'
  on-primary-fixed-variant: '#6e3900'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb68e'
  on-tertiary-fixed: '#331200'
  on-tertiary-fixed-variant: '#773300'
  background: '#111417'
  on-background: '#e1e2e7'
  surface-variant: '#323539'
typography:
  display-lg:
    fontFamily: Syne
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Syne
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Syne
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  title-lg:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0.01em
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system is engineered for creative visionaries, technical artists, and digital creators operating within high-performance generative and raster toolspaces. It unites the deep, light-swallowing density of volcanic obsidian with the dynamic micro-physics of liquid mercury and water droplets. The emotional tone balances razor-sharp creative discipline with tactile, organic fluidity—evoking the sensation of interacting with a hydrophobic precision instrument submerged in deep night.

The design movement synthesizes **Technical Glassmorphism** and **Hydrophobic Tactility**:
- **Obsidian Substrates:** Interfaces rely on light-absorbing, ultra-deep pitch black foundations to preserve color accuracy and minimize ocular fatigue during marathon creative sessions.
- **Surface Tension & Meniscus Detailing:** Interactive boundaries borrow from fluid dynamics, utilizing high-specular droplet highlights, dual-layer interior caustics, and bead-like tactile responses.
- **Luminescent Amber State Transitions:** Neutral states resting in cold technical cyans/steely tones instantly transition upon actuation into blazing soft orange and warm liquid amber (#FF9838), evoking molten glass cooled against stone.

## Colors

The palette establishes an absolute visual hierarchy anchored in darkness, illuminated by high-energy fluid accents.

### Palette Architecture
- **Primary Accent (`#ff9838`):** Liquid Amber. Used for primary call-to-actions, active toggle states, energized sliders, and critical focus triggers.
- **Secondary Accent (`#38bdf8`):** Hydro-Cyan. Reserved for idle metadata, technical readouts, measurement crosshairs, and inactive state markers before interaction.
- **Tertiary Accent (`#ff7a1a`):** Molten Coral. Applied to destructive active states, high-priority notifications, active brush strokes, and glow fringes.
- **Deep Surfaces (`#05070a`, `#0b0e14`, `#12161f`):** 
  - `Base / Canvas (`#05070a`):` Absolute abyss canvas, non-interactive backdrop.
  - `Surface Container (`#0b0e14`):` Dock panels, node graphs, toolbars, and modal surfaces.
  - `Surface Elevated (`#12161f`):` Floating controls, dropdown menus, and active tool drawers.
- **Surface Stroke & Specular Meniscus:** 
  - Neutral borders: `rgba(255, 255, 255, 0.08)` simulating liquid surface tension.
  - Specular rim light: Top-edge highlights with `rgba(255, 255, 255, 0.22)`.
  - Active bead illumination: Outer glows tinted with `rgba(255, 152, 56, 0.35)`.
- **Text & Foreground:** Crisp pure optical white (`#f8fafc`) for dominant labels and titles; neutral slate (`#94a3b8`) for secondary descriptive metadata.

## Typography

The type scale orchestrates a structural rhythm between expressive forward-leaning forms and exacting computational clarity:

- **Display & Headlines (`Syne`):** Imparts artistic authority and an avant-garde studio identity. The sculptural letterforms command attention across high-level navigational modules, canvas titles, and modal headers.
- **Body & Technical Labels (`Space Grotesk`):** Provides mechanical balance and legibility within parameter controls, coordinate displays, layer stacks, and prompt inputs. Its monospaced-adjacent geometry harmonizes with tooltips and precise dimension gauges.
- **Letter Spacing:** Tighter negative tracking is enforced on large displays to feel dense and cohesive; wider positive tracking is applied to micro labels (`label-md`, `label-sm`) to guarantee immediate recognizability in micro interfaces.

## Layout & Spacing

The layout is grounded in a flexible, workspace-driven grid designed to preserve viewport real estate for the primary canvas:

- **Layout Model:** A fluid-responsive 12-column layout (collapsing to 8 columns on tablet and 4 columns on mobile). Fixed tool ribbons frame the viewport, while dynamic inspectors and parameter docks collapse or dock contextually.
- **Micro Rhythms:** Controlled strictly by a 4px/8px incremental cadence. Inner component paddings (`space-xs`, `space-sm`) create tight, droplet-like tool groupings, while spacious macro gutters (`space-lg`, `space-xl`) isolate the creative canvas from operational telemetry.
- **Viewport Constraints:** Floating docks adhere to fixed safe margin perimeters (`margin-desktop`), floating 24px above bottom anchors to preserve the sensation of water beads resting on polished stone.

## Elevation & Depth

Visual depth is achieved through liquid refraction, surface tension, and light bleed rather than conventional drop shadows:

- **Level 0 (Abyss):** Color `#05070a`. Void layer, non-refractive.
- **Level 1 (Obsidian Slab):** Color `#0b0e14`, overlaid with a 1px composite border (`border-top: rgba(255, 255, 255, 0.12)`, `border-bottom: rgba(0, 0, 0, 0.8)`). This simulates an angled glass bevel.
- **Level 2 (Liquid Glass Floating Docks):** Background `rgba(18, 22, 31, 0.72)` supported by `backdrop-filter: blur(18px) saturate(180%)`. Outlined with a continuous 1px hydrophobic meniscus stroke `rgba(255, 255, 255, 0.08)`. Subtle ambient shadow: `0 8px 32px -4px rgba(0, 0, 0, 0.75)`.
- **Level 3 (Suspended Droplets & Popovers):** Background `rgba(22, 28, 40, 0.85)` with `backdrop-filter: blur(28px)`. Inner caustic reflection: `inset 0 1px 1px 0 rgba(255, 255, 255, 0.25)`, `inset 0 -1px 1px 0 rgba(0, 0, 0, 0.5)`. Outer cast shadow: `0 16px 40px -6px rgba(0, 0, 0, 0.9)`.
- **Active Energized Glow:** Interactive components triggered into active mode shed standard shadows in favor of a soft amber photonic halo: `0 0 24px -2px rgba(255, 152, 56, 0.35)`.

## Shapes

The geometry follows the physical rules of cohesive fluid droplets:

- **Hydrophobic Radii:** Curved boundaries mirror cohesive surface tension—moderately rounded (`roundedness: 2`, 0.5rem base radius) to ensure buttons, chips, and docks appear organically condensed rather than rigid.
- **Pill Accents:** Micro controls, segment items, and tool selectors transition into full pills (`rounded-full`) to represent self-contained liquid beads.
- **Meniscus Edge Treatment:** All bordered surfaces employ a dual-tone border effect: an acute highlight along the upper/left vector fading into an ambient dark rim along the baseline to complete the droplet look.

## Components

### Buttons
- **Liquid Glass Primary:** Rendered in `rgba(255, 152, 56, 0.15)` with a solid `#ff9838` active fluid wash. Outlined with a 1px border gradient transitioning from `rgba(255, 255, 255, 0.4)` on top to `rgba(255, 152, 56, 0.2)` on bottom. Hover state produces an amber meniscus bloom (`box-shadow: 0 0 16px rgba(255, 152, 56, 0.4)`).
- **Secondary / Ghost Bead:** Dark translucent fill (`rgba(18, 22, 31, 0.6)`), hydrophobic white rim (`rgba(255, 255, 255, 0.08)`). On hover, rim illuminates to cool hydro-cyan (`#38bdf8`), shifting to warm amber when activated.

### Chips & Filters
- Compact pill-shaped elements featuring an inner highlight dot. Inactive chips display cold slate typography with deep `#0b0e14` fills. Active filter chips switch dynamically to high-contrast white text over an amber gradient fill with an active liquid bead indicator.

### Segmented Controls & Toggles
- **Toggles:** Track begins as cool steel blue-black (`rgba(56, 189, 248, 0.15)` with `#38bdf8` tick indicators). Upon activation, the toggle track transitions through a luminous thermal shift to blazing warm amber (`#ff9838`). The knob features an ultra-glossy droplet dome with an inner convex white highlight.

### Sliders (Brush, Opacity, Guidance Scale)
- Track rendered as a 4px recessed obsidian trench. Filled portion pulses in vivid `#ffaa4a` with a blurred underglow. Thumb is styled as an overhanging hydrophobic bead that magnifies values on touch or hover.

### Inputs & Prompt Fields
- Grounded in pitch black `#05070a` with an inset shadow simulating a carven basin. Border features `rgba(255, 255, 255, 0.06)`. On focus, the field acquires an amber droplet contour (`border-color: #ff9838`) with an expansive radial back-glow.

### Cards & Tool Palettes
- Layered panels constructed from `#0b0e14` with frosted glass overlay bars. Header rows feature a crisp glass separation line (`1px solid rgba(255, 255, 255, 0.05)`). Minimized tool docks mimic floating condensation beads along the canvas periphery.