---
name: Obsidian Lumina
colors:
  surface: '#131318'
  surface-dim: '#131318'
  surface-bright: '#39383e'
  surface-container-lowest: '#0e0e13'
  surface-container-low: '#1b1b20'
  surface-container: '#1f1f25'
  surface-container-high: '#2a292f'
  surface-container-highest: '#35343a'
  on-surface: '#e4e1e9'
  on-surface-variant: '#cbc3d7'
  inverse-surface: '#e4e1e9'
  inverse-on-surface: '#303036'
  outline: '#958ea0'
  outline-variant: '#494454'
  surface-tint: '#d0bcff'
  primary: '#d0bcff'
  on-primary: '#3c0091'
  primary-container: '#a078ff'
  on-primary-container: '#340080'
  inverse-primary: '#6d3bd7'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#fbabff'
  on-tertiary: '#580065'
  tertiary-container: '#e14ef6'
  on-tertiary-container: '#4d0059'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#5516be'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#ffd6fd'
  tertiary-fixed-dim: '#fbabff'
  on-tertiary-fixed: '#36003e'
  on-tertiary-fixed-variant: '#7c008e'
  background: '#131318'
  on-background: '#e4e1e9'
  surface-variant: '#35343a'
typography:
  display-xl:
    fontFamily: Syne
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md-mobile:
    fontFamily: Syne
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: 0em
  headline-sm:
    fontFamily: Syne
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: 0em
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Geist
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-mono:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.12em
  label-mono-sm:
    fontFamily: Space Mono
    fontSize: 10px
    fontWeight: '400'
    lineHeight: 14px
    letterSpacing: 0.15em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

This design system embodies the tension between high-concept cinematic direction and cutting-edge digital production. Designed for an auteur filmmaker and studio visionary, the visual environment is dark, atmospheric, and high-contrast, evoking a calibrated production suite at midnight or an immersive theater pavilion. 

The aesthetic synthesizes futuristic brutalism with refined dark-mode glassmorphism. Surfaces feel monolithic yet weightless, using deep obsidian backdrops illuminated by spectral gradients of electric violet, neon cyan, and searing magenta. The emotional tone is authoritative, enigmatic, and hyper-premium—positioning every video reel, frame capture, and project brief as an artifact of fine digital craft.

## Colors

The palette operates on three deliberate planes: light-absorbent backdrops, luminescent spectral accents, and surgical typographic neutrals.

- **Background Obsidian Surfaces**: Canvas base `#09090e`, secondary elevated backdrop `#0d0f18`, tertiary card layer `#131524`. These absorb light, providing depth without flattening into pure zero-value black.
- **Accents & Luminescence**: Electric violet (`#8b5cf6` and deep violet `#7c3aed`) leads primary interactive elements and focus states. Neon cyan (`#06b6d4`) and electric blue (`#3b82f6`) provide technical clarity, timeline highlights, and active telemetry. Vivid magenta (`#d946ef`) acts as a catalytic tertiary highlight reserved for awards, live status indicators, and hover blooms.
- **Neutrals & Chrome**: Text runs from `#f8fafc` (high-clarity display headline white) down to `#94a3b8` (body content) and `#475569` (technical subtext and metadata). Borders rely on low-opacity strokes (`rgba(255, 255, 255, 0.08)` to `rgba(139, 92, 246, 0.3)`) to maintain razor-thin glass contours without visual bulk.

## Typography

The typographic hierarchy creates a deliberate tension between avant-garde cinematic presence and computational precision:

- **Display & Headlines (Syne)**: Expressive, structural, and wide. Headlines project confidence and auteur scale. Large titles benefit from tight letter spacing and sentence or uppercase treatments depending on context.
- **Body & Documentation (Geist)**: Pure neutral legibility. Geist recedes into the background, providing maximum readability for film treatments, narrative summaries, and technical director notes.
- **Labels, Telemetry & Metadata (Space Mono)**: Monospaced uppercase labels communicate aspect ratios (`2.39:1`), timecodes (`00:14:22:08`), film stocks, camera bodies (`ARRI ALEXA 35`), and project coordinates with strict mathematical rhythm.

## Layout & Spacing

The layout model runs on a structured 12-column fluid grid designed for widescreen showcase presentation:

- **Desktop (1200px+)**: 12 columns with `2.5rem` gutters and generous `4rem` outer canvas padding, allowing hero video units and full-bleed framing to breathe with cinema-grade aspect ratios.
- **Tablet (768px - 1199px)**: 8 columns with `1.5rem` gutters and `2rem` margins, collapsing complex multi-column telemetry into dual-column cards.
- **Mobile (below 768px)**: 4 columns with `1rem` gutters and `1.25rem` margins. Complex metadata stacks vertically beneath video stills.
- **Rhythm**: Element clusters scale according to `space-xs` through `space-xl`. Grouped metadata pairs use `space-xs` to `space-sm`, while cinematic section dividers expand dynamically to multi-tier multiples of `space-xl` (80px–120px) to establish contemplative negative space.

## Elevation & Depth

Visual hierarchy does not use traditional drop shadows. Instead, it relies on light emission, optical glass filtration, and edge refraction:

- **Base Layer (Ground)**: Pure deep obsidian (`#09090e`), static and absorption-focused.
- **Glass Surfaces (Backdrop Blur)**: Mid-tier panels utilize `rgba(13, 15, 24, 0.65)` coupled with `backdrop-filter: blur(20px)` and an internal top-lit linear gradient highlight (`rgba(255, 255, 255, 0.05)` to transparent).
- **Edge Illumination**: Boundaries are defined by a 1px composite outline (`rgba(255, 255, 255, 0.08)` resting, transitioning to `rgba(139, 92, 246, 0.5)` on hover or active states).
- **Atmospheric Glows**: Interactive focal points, video playback centers, and primary CTA buttons cast diffuse ambient halos (`box-shadow: 0 0 35px -5px rgba(139, 92, 246, 0.25)` or cyan variants `rgba(6, 182, 212, 0.2)`), simulating light spilling onto the studio desk.

## Shapes

The design system adopts a disciplined, low-radius curvature (Soft, `roundedness: 1`). 

- Default elements, small buttons, and metadata chips adhere to `0.25rem` (4px).
- Larger media cards, cinema viewport containers, and modal dialogs extend to `rounded-lg` (`0.5rem` / 8px).
- This restrained geometry preserves an architectural, high-precision apparatus feel reminiscent of luxury film equipment and audio consoles, avoiding the casual friendliness of excessive pill shapes or round corners.

## Components

- **Buttons**:
  - *Primary Action*: High-contrast solid violet background (`#8b5cf6`), bold dark text (`#09090e`), subtle `0 0 20px rgba(139, 92, 246, 0.4)` glow. Hover activates an upward scale and shift to luminous neon magenta.
  - *Secondary / Ghost*: Dark translucent fill (`rgba(19, 21, 36, 0.8)`), 1px border stroke (`rgba(255, 255, 255, 0.12)`), text in `#f8fafc`. Hover transitions border to cyan (`#06b6d4`) with faint matching backlight glow.
- **Chips & Tags**:
  - Compact height, styled with `label-mono-sm` typography. Dark neutral fill (`rgba(255, 255, 255, 0.04)`), hairline border (`rgba(255, 255, 255, 0.08)`), text `#94a3b8`. When indicating status (e.g., `IN POST-PRODUCTION` or `DIRECTOR'S CUT`), features a 6px glowing dot colored in electric magenta or cyan.
- **Media Showcase Cards**:
  - 16:9 or 2.39:1 aspect ratio containers over surface `#131524` with 8px radius. Features an inner shadow overlay protecting headline legibility, with interactive video reel playback on hover. Outer border blooms subtly into violet-blue gradient light when engaged.
- **Lists & Credit Indexes**:
  - High-density tabular layouts with 1px border dividers (`rgba(255, 255, 255, 0.06)`). Left side displays production year and role in `label-mono`, center displays project title in `headline-sm`, right side reveals client/production house and interactive trailer trigger icon.
- **Input Fields**:
  - Deep obsidian input field (`#09090e`), inset 1px border (`rgba(255, 255, 255, 0.1)`), placeholder text in `#475569`. Focused state engages neon cyan border stroke (`#06b6d4`) with a soft localized glow.
- **Interactive Scrubber / Timeline**:
  - Bespoke video portfolio scrubber bar: hairline track (`rgba(255, 255, 255, 0.1)`), completed segment highlighted in gradient violet-to-cyan, thumb marker styled as a 2px vertical luminous white blade with timecode readout tooltip in `Space Mono`.