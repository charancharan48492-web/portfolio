---
name: Obsidian Kinetic
colors:
  surface: '#10131a'
  surface-dim: '#10131a'
  surface-bright: '#363941'
  surface-container-lowest: '#0b0e15'
  surface-container-low: '#191b23'
  surface-container: '#1d1f27'
  surface-container-high: '#272a32'
  surface-container-highest: '#32353d'
  on-surface: '#e1e2ec'
  on-surface-variant: '#bdc8d1'
  inverse-surface: '#e1e2ec'
  inverse-on-surface: '#2d3038'
  outline: '#87929a'
  outline-variant: '#3e484f'
  surface-tint: '#7bd0ff'
  primary: '#8ed5ff'
  on-primary: '#00354a'
  primary-container: '#38bdf8'
  on-primary-container: '#004965'
  inverse-primary: '#00668a'
  secondary: '#b4c5ff'
  on-secondary: '#002a78'
  secondary-container: '#0053db'
  on-secondary-container: '#cdd7ff'
  tertiary: '#afcfff'
  on-tertiary: '#00315d'
  tertiary-container: '#7bb4ff'
  on-tertiary-container: '#00457e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c4e7ff'
  primary-fixed-dim: '#7bd0ff'
  on-primary-fixed: '#001e2c'
  on-primary-fixed-variant: '#004c69'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#d4e3ff'
  tertiary-fixed-dim: '#a4c9ff'
  on-tertiary-fixed: '#001c39'
  on-tertiary-fixed-variant: '#004883'
  background: '#10131a'
  on-background: '#e1e2ec'
  surface-variant: '#32353d'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  code-inline:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.01em
  label-badge:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-button:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system embodies a modern, technical, and high-precision visual identity tailored for a premier software engineer's portfolio. Its personality balances razor-sharp engineering credibility with refined, high-end digital aesthetics: confident, minimalist, deeply functional, and visually striking.

The style converges on dark-mode minimalism elevated by subtle glassmorphism and luminous electric blue accents. It eschews decorative clutter, prioritizing architectural whitespace, translucent surface depth, low-friction readability, and crisp interactions. Every detail conveys rigor, modern toolchain expertise, and digital polish without overwhelming the visitor.

## Colors
The palette leverages a deep, abyss-grade neutral foundation with layered midnight blues, accented by an electric sky-to-sapphire gradient spectrum.

- **Base Surfaces**: The primary backdrop is grounded at `#0A0D14`, transitioning to `#0F172A` for elevated card panels and structural wrappers.
- **Electric Accents**: Primary actions and vital data signals use electric sky blue (`#38BDF8`), supported by structural interactive blues (`#2563EB`) and soft hover/illumination highlights (`#60A5FA`).
- **Text & Hierarchy**: Primary typography uses high-clarity off-white (`#F8FAFC`). Secondary text recedes cleanly with slate tone (`#94A3B8`), while muted metadata uses `#64748B`.
- **Border Gradients & Strokes**: Translucent white strokes (`rgba(255, 255, 255, 0.08)`) with selective edge highlights illuminated by `#38BDF8` at low opacity (`rgba(56, 189, 248, 0.25)`).

## Typography
Typography relies on crisp geometric precision: `Inter` governs all editorial, narrative, and heading copy, while `JetBrains Mono` provides a surgical developer aesthetic for technical chips, metrics, code snippets, and system metadata.

Large headings employ tight negative letter-spacing for an authoritative editorial impact. Optical balance must be maintained across viewports by swapping display units on screens narrower than 768px via dedicated mobile scales.

## Layout & Spacing
The layout follows a 12-column responsive fluid grid maxing out at a 1200px inner container to keep technical text legible and structured.

- **Desktop (>= 1024px)**: 12-column grid, 1.5rem gutters, 3rem exterior margins. Section blocks maintain generous 5rem to 7rem vertical padding.
- **Tablet (768px - 1023px)**: 8-column layout, 1.25rem gutters, 2rem exterior margins.
- **Mobile (< 768px)**: 4-column layout, 1rem gutters, 1.25rem margin. Cards collapse to full-width stacks, and side-by-side action items switch into full-width vertical arrangements.

## Elevation & Depth
Depth is constructed through ambient luminance and frosted translucent planes rather than heavy drop shadows:

- **Backdrop Canvas**: `#0A0D14` with subtle radial lighting or low-opacity mesh glows in primary cyan (`#38BDF8`) blurred to 120px.
- **Layer 1 (Card & Content Panels)**: `rgba(15, 23, 42, 0.65)` layered with `backdrop-filter: blur(16px)` and a continuous 1px outline of `rgba(255, 255, 255, 0.08)`.
- **Layer 2 (Hover & Elevated Overlays)**: Surface lightens to `rgba(30, 41, 59, 0.75)` with an interior glow `box-shadow: inset 0 1px 0 0 rgba(255, 255, 255, 0.12), 0 8px 32px -4px rgba(0, 0, 0, 0.5), 0 0 16px 0 rgba(56, 189, 248, 0.15)`.
- **Accent Glow**: Interactive highlights emit a soft, diffused cyan aura: `0 0 24px -2px rgba(56, 189, 248, 0.3)`.

## Shapes
The shape language uses balanced curvature with distinctive pill-shaped interactive anchors:
- **Cards, Panels & Containers**: Built with `rounded-lg` (1rem / 16px) or `rounded-xl` (1.5rem / 24px) to retain an organic yet clean container frame.
- **Action Buttons & Tech Chips**: Use fully rounded pill outlines (`border-radius: 9999px`) to create an athletic, tactile, and distinct contrast against structural rectangular content containers.
- **Inputs & Badges**: Retain smooth 8px to 12px radiuses for precise alignment.

## Components

### Buttons
- **Primary Pill**: Fully rounded (`rounded-full`), background gradient `linear-gradient(135deg, #38BDF8 0%, #2563EB 100%)`, text `#0A0D14` (semi-bold) or high-contrast `#FFFFFF`. Features an ambient blue aura on hover with a slight scale transform (`1.02`).
- **Secondary / Ghost Pill**: Fully rounded, background `rgba(255, 255, 255, 0.04)`, 1px border `rgba(255, 255, 255, 0.12)`, text `#F8FAFC`. On hover, border switches to `rgba(56, 189, 248, 0.5)` with background `rgba(56, 189, 248, 0.08)`.

### Tech Badge Chips
- Rendered in `JetBrains Mono` (`label-badge`), uppercase, padding `0.25rem 0.75rem`.
- Encased in a pill silhouette with background `rgba(56, 189, 248, 0.06)`, border `1px solid rgba(56, 189, 248, 0.2)`, text `#38BDF8`.
- Optional dot indicator: a 6px circular green or cyan LED with soft pulse glow for active project status or skill level.

### Cards & Project Tiles
- Glassmorphic panels: `background: rgba(15, 23, 42, 0.6)`, `backdrop-filter: blur(12px)`, `border: 1px solid rgba(255, 255, 255, 0.07)`, `border-radius: 1rem`.
- Dynamic gradient rim lighting triggers on hover, shifting the border gradient toward `#38BDF8` while projecting an ambient slate drop-shadow.

### Inputs & Contact Elements
- Dark inset backgrounds (`rgba(10, 13, 20, 0.7)`), 1px stroke `rgba(255, 255, 255, 0.1)`, `border-radius: 0.75rem`, text `#F8FAFC`.
- Focus state activates an electric blue ring: `box-shadow: 0 0 0 2px rgba(56, 189, 248, 0.4)`, with border color transitioning to `#38BDF8`.

### Checkboxes & Radios
- Grounded base in `rgba(15, 23, 42, 0.9)`, border `rgba(255, 255, 255, 0.2)`, transitioning when checked to fill `#38BDF8` with a contrasting dark `#0A0D14` check icon.

### Metrics & Stat Counters
- Technical callouts featuring numeric metrics in `Inter` semi-bold paired with a `JetBrains Mono` muted label below, separated by subtle horizontal hairline divides (`rgba(255, 255, 255, 0.06)`).