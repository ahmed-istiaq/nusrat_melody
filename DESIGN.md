---
name: Luminous Dreamwave
colors:
  surface: '#14121b'
  surface-dim: '#14121b'
  surface-bright: '#3b3842'
  surface-container-lowest: '#0f0d16'
  surface-container-low: '#1c1a24'
  surface-container: '#211e28'
  surface-container-high: '#2b2933'
  surface-container-highest: '#36333e'
  on-surface: '#e6e0ee'
  on-surface-variant: '#dabfcc'
  inverse-surface: '#e6e0ee'
  inverse-on-surface: '#322f39'
  outline: '#a28a96'
  outline-variant: '#54414b'
  surface-tint: '#ffaedc'
  primary: '#ffaedc'
  on-primary: '#600049'
  primary-container: '#ff71ce'
  on-primary-container: '#730058'
  inverse-primary: '#a72683'
  secondary: '#98e1ff'
  on-secondary: '#003544'
  secondary-container: '#00cbfc'
  on-secondary-container: '#005267'
  tertiary: '#00e38e'
  on-tertiary: '#003920'
  tertiary-container: '#00bd76'
  on-tertiary-container: '#004528'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffd8eb'
  primary-fixed-dim: '#ffaedc'
  on-primary-fixed: '#3b002c'
  on-primary-fixed-variant: '#880068'
  secondary-fixed: '#b9eaff'
  secondary-fixed-dim: '#58d5ff'
  on-secondary-fixed: '#001f29'
  on-secondary-fixed-variant: '#004d62'
  tertiary-fixed: '#54ffaa'
  tertiary-fixed-dim: '#00e38e'
  on-tertiary-fixed: '#002110'
  on-tertiary-fixed-variant: '#005230'
  background: '#14121b'
  on-background: '#e6e0ee'
  surface-variant: '#36333e'
typography:
  display-lg:
    fontFamily: Outfit
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Outfit
    fontSize: 38px
    fontWeight: '700'
    lineHeight: 46px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Outfit
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Outfit
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Outfit
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Outfit
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Outfit
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Outfit
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Outfit
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Outfit
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system combines a deeply saturated, soft twilight canvas with vivid, iridescent neon energy. The atmosphere evokes a late-night cyber-lounge: cozy, playful, tactile, and immersive rather than harsh or dystopian.

### Key Characteristics
- **Emotional Resonance:** Electric yet approachable, dreamlike, delightfully animated, and premium.
- **Design Philosophy:** Frosted glass translucence layered over deep violet-black shadows, punctuated by selective, high-chroma illumination. Glows serve functional hierarchy—directing attention and confirming state transitions—rather than merely serving as ornamental noise.
- **Aesthetic Direction:** Neo-vaporwave meets modern dark-mode glassmorphism. Crisp geometric contours softened by generous radii, ambient diffused gradients, and rhythmic, glowing media waveforms.

## Colors
The palette balances an ultra-deep, velvety night background against four high-energy candy neon accents.

### Color Roles & Tokens
- **Canvas Base (`#0d0b14`):** The primary spatial void. Deep obsidian infused with warm plum undertones to avoid the sterility of pure `#000000`.
- **Canvas Elevated (`#120e24`):** Secondary layer for app shells, nested sections, and elevated backdrops.
- **Primary — Neon Pink (`#ff71ce`):** High-priority calls to action, active indicators, heart reactions, and focal pulse effects.
- **Secondary — Electric Cyan (`#01cdfe`):** Interactive selections, secondary toggles, progress bars, and link highlights.
- **Tertiary — Mint Foam (`#05ffa1`):** Success states, audio track energy peaks, active playback heads, and status indicators.
- **Quaternary Accent — Soft Buttercup (`#fffb96`):** Bookmarks, warnings, spark micro-badges, and star ratings.
- **Surface Overlays:**
  - Glass Layer Default: `rgba(255, 255, 255, 0.04)` with `backdrop-filter: blur(20px)`.
  - Glass Layer Elevated: `rgba(255, 255, 255, 0.08)` with subtle inner glow `inset 0 1px 1px rgba(255, 255, 255, 0.15)`.
  - Border Ghost: `rgba(255, 255, 255, 0.1)`.
  - Border Glowing: Derived dynamically from the primary or secondary hue at `35%` opacity.

## Typography
The system balances expressive, geometric personality in display titles with ultra-legible, functional clarity in body text.

- **Display & Headings (Outfit):** Delivers geometric fullness and sculpted, friendly terminals that echo the pill-shaped UI components. Display headings leverage tight negative tracking to feel cohesive and intentional under neon drop-glows.
- **Body & Data (Inter):** Neutral, tall x-height design maintains crisp contrast against dark glass layers, preventing visual fatigue across long reading sessions.
- **Labels & Micro-copy (Outfit):** Uppercase and medium/bold weights add punchy, video-game arcade flair to badges, buttons, and tab labels.

## Layout & Spacing
The layout follows a fluid 12-column grid on desktop/tablet and a 4-column system on mobile devices, underpinned by an 8pt base grid rhythm.

### Grid & Breakpoints
- **Desktop (>= 1200px):** 12 columns, max-width `1280px`, `gutter: 1.5rem`, `margin: 2rem`. Floating glass containers sit over ambient color spheres.
- **Tablet (768px – 1199px):** 8 columns, `gutter: 1.25rem`, `margin: 1.5rem`. Side navigation condenses into a translucent floating dock.
- **Mobile (< 768px):** 4 columns, `gutter: 1rem`, `margin: 1.25rem`. Content stacks vertically into glass list rails. Navigation shifts to a bottom-anchored frosted tab bar with safe-area insets.

## Elevation & Depth
Elevation eschews flat, opaque drops in favor of luminous multi-stop illumination and frosted depth. Surfaces sit at varied distances from the deep backdrop, casting colored refraction.

### Elevation Hierarchy
1. **Level 0 (Canvas):** Pure `#0d0b14` featuring blurred radial ambient spotlights (e.g., `#ff71ce` at 12% opacity, `#01cdfe` at 10% opacity, 120px blur).
2. **Level 1 (Cards & Modules):** Background `rgba(18, 14, 36, 0.65)`, backdrop-filter `blur(16px)`, border `1px solid rgba(255, 255, 255, 0.08)`. Shadow: `0 8px 32px 0 rgba(0, 0, 0, 0.37)`.
3. **Level 2 (Popovers & Active Floating Elements):** Background `rgba(28, 22, 54, 0.8)`, backdrop-filter `blur(24px)`, border `1px solid rgba(255, 255, 255, 0.16)`. Shadow: `0 12px 40px rgba(0, 0, 0, 0.6)`.
4. **Neon Glow Casts:** Interactive elements emit a soft light bleed:
   - Primary: `0 0 20px rgba(255, 113, 206, 0.45)`.
   - Secondary: `0 0 20px rgba(1, 205, 254, 0.45)`.
   - Accent: `0 0 20px rgba(5, 255, 161, 0.4)`.

## Shapes
A pill-shaped, ultra-friendly contour language runs through the entire experience (`roundedness: 3`).

- Buttons, chips, input frames, and search bars use fully rounded pill profiles (`9999px`).
- Surface cards and modal dialogs utilize generous curves (`1.5rem` to `2rem`), preventing any visual aggression.
- Subtle inner highlights on pill borders mimic the specular reflection of blown neon tubing.

## Components

### Buttons
- **Primary Neon:** Filled gradient from `#ff71ce` to `#f046b8`, text `#0d0b14` (semi-bold Outfit). Soft ambient glow `0 0 24px rgba(255, 113, 206, 0.5)`. On hover, scale `1.03` with amplified aura.
- **Secondary Glass:** Background `rgba(255, 255, 255, 0.06)`, border `1px solid rgba(1, 205, 254, 0.4)`, text `#01cdfe`. On hover, border switches to full cyan saturation with cyan shadow bloom.
- **Ghost/Tertiary:** Text `#fffb96`, background transparent. Hover reveals `rgba(255, 251, 150, 0.08)`.

### Chips & Badges
- Pill-shaped badges with `backdrop-filter: blur(8px)`.
- Live/Status badges use a pulsing dot (`#05ffa1`) paired with uppercase `label-sm` typography and a faint tinted container background (`rgba(5, 255, 161, 0.1)`).

### Input Fields
- Enclosed pill shell (`height: 48px`), background `rgba(255, 255, 255, 0.04)`, border `1px solid rgba(255, 255, 255, 0.12)`, placeholder text `rgba(255, 255, 255, 0.35)`.
- **Focus State:** Border changes to `#01cdfe` accompanied by an outer radial ring `0 0 0 3px rgba(1, 205, 254, 0.25)`. Smooth 200ms cubic-bezier transition.

### Checkboxes & Radios
- Checkbox: Custom rounded square (`radius: 8px`), unchecked border `rgba(255, 255, 255, 0.25)`. Checked state transitions to a vibrant gradient fill (`#ff71ce`) with a white micro checkmark and pink ambient glow.
- Radio: Full circle with a floating inner neon dot on active selection.

### Cards
- Framed in frosted glass (`rgba(18, 14, 36, 0.7)`), inset white hairline stroke at top edge for simulated glass refraction.
- Interactive cards feature a hover lift (`translateY(-4px)`) and a soft neon border highlight shifting to the nearest accent color.

### Smooth Tabs
- Segmented container with a dark frosted trench (`rgba(0, 0, 0, 0.3)`).
- Active tab features a sliding neon pill indicator (`rgba(255, 255, 255, 0.1)` or solid `#ff71ce` with dark text) that smoothly glides with spring physics (`stiffness: 400`, `damping: 30`).

### Glowing Audio Waveforms
- Visualizer bars styled with pill-capped strokes (`width: 3px` to `4px`, `border-radius: 9999px`).
- Unplayed track segment: `rgba(255, 255, 255, 0.15)`.
- Played track segment: Linear gradient from `#01cdfe` transitioning to `#05ffa1` with a dynamic drop-glow matching the playback intensity.
- Playhead thumb: Circular pearl `#ffffff` encased in a pulsing `#05ffa1` halo.