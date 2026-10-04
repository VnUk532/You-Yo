---
name: Tender Modernist
colors:
  surface: '#fff8f7'
  surface-dim: '#e8d6d4'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ef'
  surface-container: '#fceae8'
  surface-container-high: '#f6e4e2'
  surface-container-highest: '#f0dfdd'
  on-surface: '#221919'
  on-surface-variant: '#584140'
  inverse-surface: '#382e2d'
  inverse-on-surface: '#ffedeb'
  outline: '#8c706f'
  outline-variant: '#e0bfbd'
  surface-tint: '#ae2f34'
  primary: '#ae2f34'
  on-primary: '#ffffff'
  primary-container: '#ff6b6b'
  on-primary-container: '#6d0010'
  inverse-primary: '#ffb3b0'
  secondary: '#9d422c'
  on-secondary: '#ffffff'
  secondary-container: '#fd8c70'
  on-secondary-container: '#742411'
  tertiary: '#8e4e14'
  on-tertiary: '#ffffff'
  tertiary-container: '#d6894a'
  on-tertiary-container: '#522800'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b0'
  on-primary-fixed: '#410006'
  on-primary-fixed-variant: '#8c1520'
  secondary-fixed: '#ffdad2'
  secondary-fixed-dim: '#ffb4a2'
  on-secondary-fixed: '#3c0700'
  on-secondary-fixed-variant: '#7e2c17'
  tertiary-fixed: '#ffdcc4'
  tertiary-fixed-dim: '#ffb780'
  on-tertiary-fixed: '#2f1400'
  on-tertiary-fixed-variant: '#6f3800'
  background: '#fff8f7'
  on-background: '#221919'
  surface-variant: '#f0dfdd'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-sm: 0.75rem
  margin: 1.25rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style

This design system crafts an intimate, safe, and warm digital sanctuary for two people. It rejects transactional, clinical layouts in favor of an inviting, soft-spoken domestic elegance. 

### Visual Character
- **Emotional Resonance**: Warmth, tenderness, emotional safety, shared rituals, gentle anticipation.
- **Style Archetype**: Warm Romantic Minimalism merged with tactile, pillowy card surfaces.
- **Atmosphere**: Velvety, calm, and uncluttered. Surfaces mimic smooth ceramic stones, high-grade linen, and soft ambient daylight.
- **Accents**: Interlocking avatar rings, subtle heart badges, anniversary counters, and mutual state pulses (e.g., "Thinking of you").

## Colors

The palette is tuned around warm peach-coral transitions and calming, low-contrast neutral backdrops that soothe eye fatigue during late-night bedtime chats.

- **Primary (`#FF6B6B`)**: Deep Rose Coral. Applied to primary emotional actions (sending love taps, affirming rituals, core CTA buttons).
- **Secondary (`#FF8E72`)**: Pastel Peach-Sunburst. Used in paired gradients, celebration states, and secondary visual tags.
- **Tertiary (`#F4A261`)**: Warm Apricot Sand. Reserved for memory highlights, milestone celebrations, and calendar events.
- **Neutral (`#5A4E4D`)**: Deep Cocoa Taupe. Replaces harsh blacks for all typography and structural lines, retaining warmth and legibility across all backgrounds.
- **Surface Canvas**: `#FFF9F6` (Sunlit Blush) base layer, with `#FDF6F0` (Alabaster Linen) for nested wells and cards.

## Typography

The pairing combines the geometric, friendly warmth of **Plus Jakarta Sans** for expressive displays, titles, and emotive buttons, with the neutral, effortless legibility of **Inter** for long-form love letters, daily prompt journals, and shared checklists.

- Use **display** exclusively for milestone counters (e.g., "520 days together").
- Set headings with subtle negative letter-spacing to tighten optical flow.
- Maintain soft line-heights on body copy to preserve breathability and calm.

## Layout & Spacing

A mobile-first system designed for single-handed usage and cozy, glanceable interaction.

- **Grid Strategy**: Fluid 4-column layout on compact mobile screens, transitioning to an 8-column centralized container (max-width 540px) when viewed on tablets or foldables.
- **Vertical Rhythm**: Built upon an 8pt base unit. Inner card gaps maintain standard intervals (`space-md`), creating a predictable sense of rest and order.
- **Thumb Reachability**: Key intimate actions (quick reaction triggers, shared notes drawer) dock in the lower 35% of the viewport.

## Elevation & Depth

Visual hierarchy uses warm, diffuse illumination instead of sharp drop shadows.

- **Ambient Shading**: Avoid cool grays. Shadows are tinted with the primary hue: `rgba(255, 107, 107, 0.08)` to `rgba(90, 78, 77, 0.06)`, with generous blur radii (16px to 32px) and minimal vertical offset (4px to 8px).
- **Surface Layering**: 
  - `Level 0`: Pure Canvas (`#FFF9F6`).
  - `Level 1`: Floating Cards (`#FFFFFF`) with 1px border `rgba(255, 142, 114, 0.15)`.
  - `Level 2`: Interactive Overlays & Drawers (`#FFFFFF`) backed by a tinted blur backdrop (`backdrop-filter: blur(12px)` over `rgba(255, 249, 246, 0.8)`).
- **Ghost Outlines**: Hairline borders are soft blush tones, never high-contrast stroke dividers.

## Shapes

The shape system adopts pillowy, generous curvature to evoke tenderness, comfort, and tactility.

- **Cards and Containers**: Employ `rounded-xl` (1.5rem / 24px) to `rounded-2xl` (2rem / 32px) for major widgets (Counter, Memory Lane, Mood Board).
- **Interactive Pills**: Buttons, chips, and quick-tag elements strictly utilize full circular/capsule boundaries (`rounded-full`).
- **Nesting Ratio**: When cards contain nested interactive blocks, the child radius is adjusted inward to maintain visual harmony (e.g., 28px card wrapping 18px inner chips).

## Components

### Buttons
- **Primary**: Full pill-shaped CTA with a subtle warm gradient (`linear-gradient(135deg, #FF6B6B 0%, #FF8E72 100%)`), white label text, and an ambient coral glow on active press.
- **Secondary / Soft**: Subtle peach background (`rgba(255, 142, 114, 0.15)`) with deep coral text (`#FF6B6B`). No harsh outline.

### Avatar Pair Rings
- Overlapping dual avatar circles (48px each, 12px overlap).
- Bordered by a 3px solid `#FFF9F6` separator ring.
- Connected via a centered micro heart badge (16px) floating at the lower overlap point, tinted in `#FF6B6B` with a gentle breathing pulse animation.

### Romantic Counter Widget
- Elevated pure white card featuring dynamic relationship milestones ("Day 482", "3 years, 2 months").
- Large display numerals in `#5A4E4D`, accompanied by micro-labels in uppercase `label-sm` tracking.
- Subtle background illustration of delicate interconnected rings or abstract wavy hearts tinted at 5% opacity.

### Cozy Status Chips
- Pill chips displaying reciprocal moods (e.g., "Miss you ✨", "Resting ☕", "Home soon 🏡").
- Active mood utilizes soft peach fill with a 6px status circle indicator. Inactive moods feature an ultra-light taupe-blush tint.

### Input Fields
- Enclosed pill and squircle inputs with deep cream backgrounds (`#FDF6F0`).
- Borderless in neutral state; transition to a 1.5px soft coral outline (`#FF8E72`) on focus, without hard rings.
- Helper text and icons utilize `#5A4E4D` at 60% opacity.

### Checkboxes & Shared Lists
- Checkboxes are smoothed circles with custom soft coral fill and white heart checkmarks instead of standard angular ticks.
- Completed list items transition text to warm muted taupe with a playful soft-strike line.