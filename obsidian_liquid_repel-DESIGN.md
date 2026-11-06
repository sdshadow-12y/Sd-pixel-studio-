---
name: Obsidian Liquid Repel
colors:
  surface: '#111319'
  surface-dim: '#111319'
  surface-bright: '#37393f'
  surface-container-lowest: '#0c0e13'
  surface-container-low: '#191c21'
  surface-container: '#1d2025'
  surface-container-high: '#282a30'
  surface-container-highest: '#32353b'
  on-surface: '#e1e2ea'
  on-surface-variant: '#bbc9cf'
  inverse-surface: '#e1e2ea'
  inverse-on-surface: '#2e3036'
  outline: '#859399'
  outline-variant: '#3c494e'
  surface-tint: '#47d6ff'
  primary: '#a5e7ff'
  on-primary: '#003543'
  primary-container: '#00d2ff'
  on-primary-container: '#00566a'
  inverse-primary: '#00677f'
  secondary: '#7bd0ff'
  on-secondary: '#00354a'
  secondary-container: '#00a6e0'
  on-secondary-container: '#00374d'
  tertiary: '#c1e0ff'
  on-tertiary: '#003351'
  tertiary-container: '#86c7ff'
  on-tertiary-container: '#005380'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#b6ebff'
  primary-fixed-dim: '#47d6ff'
  on-primary-fixed: '#001f28'
  on-primary-fixed-variant: '#004e60'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#93ccff'
  on-tertiary-fixed: '#001d31'
  on-tertiary-fixed-variant: '#004b73'
  background: '#111319'
  on-background: '#e1e2ea'
  surface-variant: '#32353b'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.05em
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
  gutter-desktop: 1.5rem
  margin: 1.5rem
  margin-mobile: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system embodies an ultra-tactile convergence of obsidian glassmorphism, fluid refraction, and high-precision digital studio tools. Crafted for technical creatives, pixel artists, and next-generation visual computing workflows, the environment delivers an immersive darkroom atmosphere. 

The aesthetic is characterized by deep oceanic abyss voids overlaid with crystalline liquid panels. Interface boundaries mimic high surface-tension water droplets and polished vulcanized glass with micro-refractive specular highlights. Crisp, luminescent cyan and electric blue currents cut through the absolute darkness, establishing instant visual hierarchy and state feedback. The emotional resonance is ultra-focused, sophisticated, and kinetic—evoking the feeling of sculpting pixels directly onto suspended fluid optics.

## Colors

The palette operates on extreme dynamic range: high-luminance refractive accents set against layered black voids.

### Foundations & Canvas
- **Abyss Void (Canvas Base):** `#030407` — Infinite background depth, grounding viewport panes and viewports.
- **Obsidian Core (Main Surface):** `#06080d` — Structural panels, primary viewport backdrops.
- **Obsidian Layer (Sub-Surface):** `#0b0f19` — Floating inspector palettes, nested controls, sidebars.

### Fluid Accents
- **Electric Cyan (Primary):** `#00d2ff` — Primary interactive focal points, active drawing tools, liquid glow fills, and live cursor indicators.
- **Droplet Specular (Secondary):** `#38bdf8` — Secondary interactive states, specular highlights, refraction borders, and sub-selection nodes.
- **Deep Marine (Tertiary):** `#0284c7` — Deeper accent layering, pressed container fills, timeline keyframe bands, and secondary progress tracks.

### Glass Translucencies & Highlights
- **Liquid Membrane (Border Default):** `rgba(255, 255, 255, 0.08)` top/left gradient flowing into `rgba(0, 210, 255, 0.22)` bottom/right.
- **Frosted Smear (Surface Muted):** `rgba(11, 15, 25, 0.65)` with backdrop filters.
- **Specular Bead (Apex Glare):** `rgba(255, 255, 255, 0.85)` for pin-point reflections along panel edges and rounded vertices.

### Functional Neutrals
- **High-Stops (Text Primary):** `#f8fafc` — Absolute legibility on dark glass.
- **Mid-Stops (Text Secondary):** `#94a3b8` — Metadata, hotkeys, tooltips, inactive tabs.
- **Low-Stops (Text Muted):** `#475569` — Disabled states, grid coordinates, subtle division markers.

## Typography

The type system blends structural geometric display forms with technical monospaced utility:

- **Space Grotesk** commands marketing, headers, canvas titles, and modal headers. Its eccentric geometric junctions pair naturally with liquid refraction curves.
- **Geist** manages long-form documentation, project metadata, inspect panel descriptions, and tool definitions with neutral clarity.
- **JetBrains Mono** enforces numerical exactness across pixel coordinate indicators, hex pickers, transform metrics, hotkeys, and layer dimensions.

All text layers maintain a minimum contrast ratio of 7:1 against glass backdrops. In high-glare glass regions, apply a subtle text-shadow of `0 1px 2px rgba(3, 4, 7, 0.95)` to eliminate background bleed-through.

## Layout & Spacing

The layout is structured around an ultra-dense, docked workspace model paired with fluid modular canvas regions.

### Structure & Behavior
- **Desktop (>= 1280px):** Dynamic panel docking system. Persistent left tool-dock (width: 56px to 72px), canvas workspace viewport (fluid flex-1), and contextual right-side inspector/layer-stack (width: 320px to 380px). Spacing utilizes `gutter-desktop` (24px) with fixed `margin-desktop` (32px).
- **Tablet (768px - 1279px):** Floating tool palette docked to screen base. Side panels collapse into frosted liquid drawer sheets with swipe gestures.
- **Mobile (< 768px):** Single-column layout. Workspace canvas pins to viewport center; tools and menus manifest as suspended bottom-action trays utilizing `margin-mobile` (16px) and `gutter-mobile` (12px).

### Spacing Philosophy
Internal component padding relies strictly on a 4px/8px incremental base:
- `space-xs` (4px) for micro toolbars, tight color-swatch clusters, and coordinate locks.
- `space-sm` (8px) for button clusters, property inputs, and layer-tree nesting indentations.
- `space-md` (16px) for card body interiors, dialog insets, and panel content zones.
- `space-lg` (24px) for empty canvas margins and contextual drop downs.
- `space-xl` (32px) for canvas setup templates and export dialogs.

## Elevation & Depth

Visual depth is achieved through layered refractive surfaces rather than simple dropped shadows. The metaphor is light scattering through stacked sheets of coated glass over deep dark water.

### Depth Architecture

- **Surface 0 (Canvas Void):** `#030407` solid ground.
- **Surface 1 (Base Docks & Panels):** `rgba(6, 8, 13, 0.72)` background with `backdrop-filter: blur(24px) saturate(180%)`. Border: 1px solid `rgba(255, 255, 255, 0.06)`.
- **Surface 2 (Floating Cards & Droplet Modules):** `rgba(11, 15, 25, 0.80)` with `backdrop-filter: blur(32px) saturate(200%)`. Border: 1px solid `rgba(56, 189, 248, 0.18)`. Shadow: `0 8px 32px -4px rgba(0, 0, 0, 0.8), 0 0 0 1px rgba(255, 255, 255, 0.05) inset`.
- **Surface 3 (Overlays, Context Menus & Modals):** `rgba(11, 15, 25, 0.92)` with `backdrop-filter: blur(48px)`. Top edge highlight: `inset 0 1px 0 0 rgba(255, 255, 255, 0.35)`. Ambient outer shadow: `0 24px 64px -12px rgba(0, 0, 0, 0.9), 0 0 20px 0 rgba(0, 210, 255, 0.15)`.

### Liquid Refraction & Glow
Elements in an active or hovered state display dynamic edge refraction:
- Inset specular glints: `inset 1px 1px 1px 0 rgba(255, 255, 255, 0.25)`.
- Liquid electric rim: `box-shadow: 0 0 16px -2px rgba(0, 210, 255, 0.45)`.

## Shapes

The shape system mimics fluid surface tension. Shapes follow continuous curviness (squircle-like transitions) rather than rigid industrial geometry.

- **Standard Elements (Buttons, Inputs, Swatches):** `rounded` (8px / 0.5rem) ensures ergonomic touch and pointer tracking while preserving canvas screen real estate.
- **Grouped Trays, Floating Cards, Dialogs:** `rounded-lg` (16px / 1rem) replicates a large pooled droplet of water settled on a hydrophobic surface.
- **Workspace Sheets, Viewport Overlays:** `rounded-xl` (24px / 1.5rem) softens outer canvas margins.
- **Pills / Bead Badges:** Tool status indicators, zoom level capsules, and drawing mode badges use full pill profiles (`rounded-full`) to simulate isolated water beads.

## Components

### Buttons & Interactive Controls
- **Liquid Glow Primary CTA:**
  - Base: Linear gradient from `#00d2ff` to `#0284c7`.
  - Border: 1px solid `rgba(255, 255, 255, 0.4)` on top edge, transitioning to transparent.
  - Text: `#030407` with `Space Grotesk` font-weight 600.
  - Shadow: `0 4px 20px rgba(0, 210, 255, 0.4), inset 0 1px 1px rgba(255, 255, 255, 0.6)`.
  - Hover: Expand glow radius to 28px, brightness scale `108%`.
- **Secondary Glass Ghost:**
  - Base: `rgba(255, 255, 255, 0.03)` with `backdrop-filter: blur(12px)`.
  - Border: 1px solid `rgba(255, 255, 255, 0.1)`.
  - Text: `#f8fafc`.
  - Hover: Border switches to `rgba(56, 189, 248, 0.5)` with `box-shadow: 0 0 12px rgba(0, 210, 255, 0.15)`.

### Inputs & Sliders
- **Text & Numeric Inputs:**
  - Background: `rgba(6, 8, 13, 0.85)`.
  - Border: 1px solid `rgba(255, 255, 255, 0.08)`.
  - Typography: `JetBrains Mono` for pixel/coordinate values.
  - Focus State: Border switches to `#00d2ff`, specular inner glow `inset 0 0 8px rgba(0, 210, 255, 0.25)`.
- **Liquid Range Sliders:**
  - Track: 4px height, `#0b0f19` filled with a glowing cyan line representing value.
  - Thumb: 14px circular glass droplet with a pure white center core `#ffffff` and an outer halo of `rgba(0, 210, 255, 0.6)`.

### Cards & Panels
- **Inspector Tool Card:**
  - Surface: `rgba(11, 15, 25, 0.75)` frosted glass with `backdrop-filter: blur(32px)`.
  - Rim: Dual-tone border with `rgba(255, 255, 255, 0.12)` along top-left corners and `rgba(0, 210, 255, 0.2)` along bottom-right.
  - Header: Integrated hairline divider `rgba(255, 255, 255, 0.06)`.

### Chips & Badges
- **Status Beads:**
  - Height: 24px, pill-curved.
  - Background: `rgba(0, 210, 255, 0.08)`.
  - Text: `JetBrains Mono` 10px `#38bdf8`.
  - Specular Dot: 6px radial circle inside badge glowing with `#00d2ff` box-shadow.

### Checkboxes & Toggle Switches
- **Toggle Switches:**
  - Track: 36px x 20px, obsidian groove `rgba(3, 4, 7, 0.8)`.
  - Active Track: `#0284c7`.
  - Thumb: Water-droplet orb that glides across states with a 150ms cubic-bezier transition, leaving an active wake glow.
- **Checkboxes:**
  - Size: 16px x 16px, rounded 4px.
  - Checked State: Solid `#00d2ff` fill with `#030407` checkmark icon and `0 0 10px rgba(0, 210, 255, 0.5)` drop aura.

### Lists & Tree Views (Layers)
- **Pixel Layer Item:**
  - Default: Transparent fill, text `#94a3b8`.
  - Selected: Background `rgba(0, 210, 255, 0.12)`, border-left `2px solid #00d2ff`, text `#f8fafc`.
  - Hover: Subtle liquid smear `rgba(255, 255, 255, 0.04)`.
  - Visibility / Lock Toggles: Glass icons with cyan highlight on active state.

### Studio Tool Specifics (Canvas Zoom & Swatches)
- **Color Swatch Orb:**
  - Curvature: Circular, elevated 2px off panel with hydrophobic convex refraction border `inset 0 1px 2px rgba(255, 255, 255, 0.5)`.
- **Canvas Tooldock Float:**
  - Vertical liquid pillar anchored to canvas left edge; tools highlight with an internal blue-light bead that tracks the active tool smoothly.