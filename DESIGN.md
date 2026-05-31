---
name: PowerPunk Kinetic
colors:
  surface: '#121315'
  surface-dim: '#121315'
  surface-bright: '#38393b'
  surface-container-lowest: '#0d0e10'
  surface-container-low: '#1b1c1e'
  surface-container: '#1f2022'
  surface-container-high: '#292a2c'
  surface-container-highest: '#343537'
  on-surface: '#e3e2e4'
  on-surface-variant: '#ccc7ab'
  inverse-surface: '#e3e2e4'
  inverse-on-surface: '#303033'
  outline: '#959177'
  outline-variant: '#4a4732'
  surface-tint: '#d6ca00'
  primary: '#ffffff'
  on-primary: '#353100'
  primary-container: '#f4e700'
  on-primary-container: '#6d6600'
  inverse-primary: '#666000'
  secondary: '#d3fbff'
  on-secondary: '#00363a'
  secondary-container: '#00eefc'
  on-secondary-container: '#00686f'
  tertiary: '#ffffff'
  on-tertiary: '#561f00'
  tertiary-container: '#ffdbcc'
  on-tertiary-container: '#aa4500'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#f4e700'
  primary-fixed-dim: '#d6ca00'
  on-primary-fixed: '#1f1c00'
  on-primary-fixed-variant: '#4d4800'
  secondary-fixed: '#7df4ff'
  secondary-fixed-dim: '#00dbe9'
  on-secondary-fixed: '#002022'
  on-secondary-fixed-variant: '#004f54'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb693'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7a3000'
  background: '#121315'
  on-background: '#e3e2e4'
  surface-variant: '#343537'
  night-black: '#050505'
  gray-dark: '#1A1B1E'
  gray-light: '#3A3B3E'
  glitch-red: '#FF003C'
  toxic-green: '#ADFF00'
typography:
  display-xl:
    fontFamily: Anton
    fontSize: 80px
    fontWeight: '400'
    lineHeight: 80px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: 0.04em
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 32px
  headline-md:
    fontFamily: Anton
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.05em
  body-lg:
    fontFamily: Archivo Narrow
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Archivo Narrow
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.1em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.15em
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  container-max: 1440px
---

## Brand & Style

This design system embodies the "PowerPunk" ethos: a high-velocity collision between industrial energy and dystopian digital rebellion. The aesthetic is rooted in **Brutalism** and **High-Contrast Boldness**, favoring raw utility over traditional polish.

The brand personality is rebellious, urgent, and hyper-energetic. It targets a demographic that thrives on high-octane performance and "Night City" edge. Visually, this is expressed through:
- **Asymmetric Geometry:** Diagonal cuts and "glitched" offsets in containers.
- **Digital Noise:** Subtle scanline overlays and dithered gradients to simulate hardware interference.
- **Gritty Textures:** High-tech surfaces contrasted with raw, industrial grit.
- **Aggressive Motion:** UI transitions should feel like a system overclocking—fast, sharp, and intentional.

## Colors

The palette is anchored by "Cyberpunk Yellow," an aggressive, saturated primary used for critical actions and brand impact. This is supported by "Electric Blue" for data-heavy elements and "Neon Orange" for supplementary highlights.

The interface defaults to a **Dark Mode** foundation using "Night City" blacks and deep grays to ensure neon elements achieve maximum vibrance. High-contrast "Glitch Red" is reserved for destructive actions or system alerts, while "Toxic Green" indicates successful system synchronization or "energy charged" states.

## Typography

Typography is treated as industrial architecture. **Anton** provides massive, impactful headlines that command attention, while **Archivo Narrow** ensures high information density in body text without sacrificing legibility.

**JetBrains Mono** is utilized for metadata, system readouts, and UI labels to reinforce the "high-tech" hacker aesthetic. All headlines should be set in **ALL CAPS** to maintain the aggressive brand voice. Monospaced elements should frequently use prefixing (e.g., `// ACCESSING_`) to enhance the digital narrative.

## Layout & Spacing

This design system uses a **Fluid Grid** model with a hard-edged 4px baseline unit. The layout is designed to feel dense and technical, avoiding excessive whitespace in favor of "structured clusters" of information.

- **Desktop:** 12-column grid, 24px gutters. Elements should often overlap or use "negative margins" to create a layered, complex appearance.
- **Mobile:** 4-column grid, 16px margins.
- **Breakpoints:** 
  - Mobile: < 600px
  - Tablet: 600px - 1024px
  - Desktop: > 1024px

Layouts should incorporate "technical ornamentation" such as corner brackets, coordinates, and scanline borders that exist outside the standard padding to break the grid's rigidity.

## Elevation & Depth

Depth is not achieved through soft shadows or physical lighting, but through **Tonal Layering** and **High-Contrast Outlines**.

1.  **Base Surface:** Deepest black (`#050505`).
2.  **Container Surface:** Dark gray (`#1A1B1E`) with 1px solid borders using the primary or secondary neon colors.
3.  **Active Layer:** Uses "Backdrop Blurs" (12px - 20px) with 70% opacity backgrounds to create a digital glass effect.
4.  **Shadows:** When used, shadows are "Sharp Hard-Drops"—non-blurred offsets (e.g., 4px 4px 0px) in a contrasting neon color, mimicking retro-digital depth.

## Shapes

The shape language is strictly **Sharp (0px)**. 

To differentiate elements without using rounded corners, this design system utilizes **Chamfered Edges** (diagonal cuts). Containers should feature a 45-degree "clipped corner" (usually the top-left or bottom-right) to evoke a rugged, custom-machined feel. All borders must be crisp, 1px or 2px lines with no anti-aliasing on the logic of the shape itself.

## Components

### Buttons
Primary buttons are solid Cyberpunk Yellow with black text, featuring a 45-degree clip on the top-right corner. Hover states should trigger a "glitch" animation where the background shifts to Electric Blue for a fraction of a second.

### Input Fields
Dark backgrounds with a 1px bottom border in Primary Yellow. Labels must be in `label-caps` (JetBrains Mono) and positioned above the field, prefixed with a `>` symbol.

### Chips / Tags
Small, angular containers with 1px borders. Use secondary colors (Blue/Orange) for categorization. Text must be monospaced and all-caps.

### Cards
Cards use the "Night City" gray background. They feature a decorative "header bar" (2px thick) and technical corner brackets. Content inside cards is high-density.

### Lists
Lists are separated by horizontal lines with a "scanline" dither effect. Each item should have a hover state that highlights the background with a 10% opacity tint of the secondary color.

### Checkboxes & Radios
Custom geometric designs. Checkboxes are squares; Radio buttons are diamonds. Both use sharp 90-degree angles and glow with "Electric Blue" when selected.