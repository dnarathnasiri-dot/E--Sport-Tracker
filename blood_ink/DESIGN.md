---
name: Blood & Ink
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#ddc0bd'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#a58b88'
  outline-variant: '#564240'
  surface-tint: '#ffb4ab'
  primary: '#ffb4ab'
  on-primary: '#630e0d'
  primary-container: '#822621'
  on-primary-container: '#ff9a8f'
  inverse-primary: '#a23d36'
  secondary: '#ffb4ab'
  on-secondary: '#5f1511'
  secondary-container: '#802d27'
  on-secondary-container: '#ff9f94'
  tertiary: '#c9c6c0'
  on-tertiary: '#31312c'
  tertiary-container: '#474742'
  on-tertiary-container: '#b7b5af'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#822621'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#ffb4ab'
  on-secondary-fixed: '#410002'
  on-secondary-fixed-variant: '#7d2b25'
  tertiary-fixed: '#e5e2db'
  tertiary-fixed-dim: '#c9c6c0'
  on-tertiary-fixed: '#1c1c18'
  on-tertiary-fixed-variant: '#474742'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Oswald
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Oswald
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: 0.01em
  headline-lg-mobile:
    fontFamily: Oswald
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Oswald
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style
This design system represents the "Prestige" evolution of a hand-drawn aesthetic. It targets a competitive gaming audience that values grit, skill, and a "dark-mode" lifestyle. The personality is aggressive, raw, and authoritative—moving away from the playfulness of typical doodles toward a more sinister, ink-stained underground league.

The visual style is a fusion of **Tactile Brutalism** and **Gothic Minimalism**. It preserves the human touch through imperfect, "sketchy" stroke lines and torn-paper textures, but anchors them in a rigid, modern digital structure. The emotional response should be one of high stakes and intense focus, evoking the atmosphere of a clandestine tournament held in a dimly lit, industrial space.

## Colors
The palette is dominated by "Deep Blood" and "Oxblood" tones to create a high-tension, moody atmosphere.

- **Primary (#822621):** Used for critical actions, highlights, and primary brand strokes. It represents the "energy" of the league.
- **Secondary (#410002):** Used for depth, container backgrounds, and subtle gradients. It provides a bruised, heavy anchor to the brighter red.
- **Background (#0E0E0E):** A deep, near-black neutral that ensures the red tones vibrate with intensity.
- **Accents (#F4F1EA):** An off-white "Bone" or "Scrap Paper" color used sparingly for high-contrast text or tactical elements that need to feel physically superimposed over the darkness.

Color application should favor deep red-on-black combinations, using the off-white only for essential legibility or "torn-edge" UI dividers.

## Typography
The typography strategy creates a tension between "The Machine" and "The Hand."

**Headlines** utilize **Oswald** to provide a condensed, high-impact, and slightly gothic/industrial feel. All major headings should be set in uppercase to maximize their architectural presence.

**Body Text** utilizes **Inter** for maximum readability amidst the dark, high-contrast environment. It acts as the "clean" anchor that makes the system usable for complex gaming data.

**Technical Labels** utilize **JetBrains Mono** (monospaced) to lean into the developer/technical aspect of a gaming league, appearing like serial numbers or "ink-stamped" data on a dossier.

## Layout & Spacing
The layout follows a **Rigid Fluid Grid**. While individual elements (borders, dividers) may have hand-drawn "wobble," the underlying structure is a disciplined 12-column system.

- **Desktop:** 12 columns, 24px gutters, 64px side margins.
- **Mobile:** 4 columns, 16px gutters, 16px side margins.

Spacing should be generous to maintain a "prestige" feel. Use "white space" (which is actually "dark space" here) to isolate key pieces of content. UI sections should be separated by "Torn Paper" or "Rough Ink" horizontal rules rather than clean CSS borders.

## Elevation & Depth
Elevation in this system is not achieved through soft, realistic shadows, but through **Tonal Stacking** and **Tactile Overlays**.

- **Level 0 (Base):** #0E0E0E.
- **Level 1 (Containers):** #1A0001 (A very dark, red-tinted black) with a 2px "Rough Ink" border.
- **Level 2 (Popovers/Cards):** #410002 with a bold, hand-drawn stroke in #822621.

Use **inner glows** (tinted red) instead of drop shadows to make elements appear as if they are "bleeding" into the surface. Contrast is the primary driver of depth—an off-white "paper" element should look like it is physically pinned or taped to the dark background.

## Shapes
The shape language is **Sharp and Aggressive**. Rounded corners are avoided to maintain the "brutal" nature of the design.

Instead of standard border-radii, use **Clip-path** or **SVG Masks** to create "deckled edges" or "rough-cut" corners. Buttons and input fields should appear as if they were hand-cut from a dark material. Squiggles and hand-drawn flourishes should be used as decorative underlines or strike-throughs for text.

## Components

### Buttons
- **Primary:** Solid #822621 background, #F4F1EA text. The border should be an SVG "Rough Ink" stroke that slightly overshoots the corners.
- **Secondary:** Outlined with a 2px "Wobbly" stroke in #822621. Text is Primary red.
- **State Changes:** On hover, the button should "shake" slightly (2px jitter) and the background color should saturate.

### Cards & Containers
Containers should not use standard CSS borders. Use an `::after` element with a tiled SVG border that mimics a hand-drawn felt-tip pen line. Backgrounds should have a subtle "noise" or "paper texture" overlay.

### Input Fields
Dark background (#0E0E0E) with a bottom-only "Inky" border. Labels use the Monospaced font in #822621. Active states should trigger a faint red "smudge" glow behind the input.

### Chips & Badges
Small, sharp-edged rectangles using #410002 background and Primary red text. These should look like "stamps" on a document.

### Lists
List items are separated by horizontal "Ink Scratches." Bullet points are replaced with hand-drawn "X" marks or "Red Dots" that look like blood drops.