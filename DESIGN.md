---
name: BNM Studio
version: "1.1"
description: >
  Strategic Design Studio. Mexico City.
  Full creative coverage for growing companies — branding, motion, web, and strategy under one roof.
  Two principals. No intermediaries. Senior work, always.

colors:
  # --- Core palette ---
  background: "#F9F6F5"       # Off-white warm. The default canvas. Never pure white.
  surface-light: "#FFFFFF"    # Cards and panels on the warm background.
  surface-dark: "#161616"     # Dark cards, inverted sections, hero modules.
  surface-black: "#000000"    # Full-black elements when maximum contrast is needed.
  primary: "#252525"          # Near-black. Headlines, body text, primary CTAs, logo.
  muted: "#666666"            # Secondary text, captions, supporting copy only.
  border: "#252525"           # Outlines, tag borders, input borders.
  accent-primary: "#3244DD"   # Electric blue. Primary CTA color, active states, key highlights.
  accent-secondary: "#D8EF5B" # Lime green. Secondary accent, complementary highlights.
  text-on-dark: "#FFFFFF"     # Text on surface-dark or surface-black.
  text-on-accent-blue: "#FFFFFF"   # Text on accent-primary (#3244DD).
  text-on-accent-lime: "#252525"   # Text on accent-secondary (#D8EF5B). Never white — contrast fails.

  # --- RGB tokens for layered use ---
  base-rgb-light: "250, 247, 246"   # For rgba() use on light surfaces.
  accent-rgb-light: "159, 139, 231" # Soft purple tint — for glow/overlay effects on light.
  additional-rgb-light: "221, 241, 96" # Lime in RGB form.
  base-rgb-dark: "22, 22, 22"       # For rgba() use on dark surfaces.
  accent-rgb-dark: "221, 241, 96"   # Lime becomes primary accent on dark surfaces.

typography:
  display:
    fontFamily: "'Funnel Display', sans-serif"
    fontSize: "140px"
    fontWeight: 600
    lineHeight: "140px"
    letterSpacing: "-0.6px"
    notes: >
      Hero headlines only. Massive, tight, intentional.
      May fill or overflow the viewport — this is deliberate.
      The headline IS the layout. Never constrain to a column width.

  h1:
    fontFamily: "'Funnel Display', sans-serif"
    fontSize: "120px"
    fontWeight: 600
    lineHeight: "1.05"
    letterSpacing: "-0.6px"

  h2:
    fontFamily: "'Funnel Display', sans-serif"
    fontSize: "70px"
    fontWeight: 600
    lineHeight: "77px"
    letterSpacing: "-0.6px"
    notes: "Capability card headings. Section titles. Large feature labels."

  h3:
    fontFamily: "'Funnel Display', sans-serif"
    fontSize: "36px"
    fontWeight: 600
    lineHeight: "43.2px"
    letterSpacing: "normal"

  body-lg:
    fontFamily: "'Funnel Sans', sans-serif"
    fontSize: "22px"
    fontWeight: 300
    lineHeight: "35.2px"
    letterSpacing: "normal"
    notes: "Primary body copy. Light weight — the contrast with heading weight 600 is intentional."

  body-md:
    fontFamily: "'Funnel Sans', sans-serif"
    fontSize: "18px"
    fontWeight: 300
    lineHeight: "1.65"
    letterSpacing: "normal"

  label:
    fontFamily: "'Funnel Sans', sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: "1.4"
    letterSpacing: "0.04em"
    textTransform: "uppercase"
    notes: "Tags, nav items, section markers, captions."

  stat:
    fontFamily: "'Funnel Display', sans-serif"
    fontSize: "140px"
    fontWeight: 600
    lineHeight: "1.0"
    letterSpacing: "-0.6px"
    notes: "Counter blocks (50+, 80%, 9+, 2+). The number is a typographic object."

  scale:
    display: "140px"
    h1: "120px"
    h2: "100px"
    h3: "92px"
    h4: "81px"
    body-l: "70px"
    body: "56px"
    small: "50px"
    xs: "44px"
    caption: "40px"

spacing:
  base: "36px"
  "1x": "36px"
  "2x": "72px"
  "3x": "108px"
  "4x": "144px"
  element: "20px"
  card-sm: "36px"
  card-md: "42px"
  card-lg: "50px"
  section-sm: "80px"
  section-md: "90px"
  section-lg: "110px"
  content-max: "1400px"

rounded:
  sm: "18px"
  md: "26px"
  lg: "42px"
  xl: "50px"
  pill: "28px"
  circle: "99px"

animation:
  fast: "0.1s"
  medium: "0.3s"
  slow: "0.6s"
  easing: "cubic-bezier(0.23, 0.65, 0.74, 1.09)"
  notes: >
    Custom easing has a slight overshoot — confident and settled, not mechanical.
    Use for hover states, card transitions, and entrance animations.

breakpoints:
  xs: "0px"
  sm: "576px"
  md: "768px"
  lg: "992px"
  xl: "1200px"
  xxl: "1400px"

components:
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    border: "2px solid {colors.primary}"
    borderRadius: "{rounded.pill}"
    paddingX: "22px"
    fontSize: "22px"
    fontWeight: 600
    notes: "Nav CTA ('Say Hello ↗'). Outline pill on light background."

  button-outline-dark:
    backgroundColor: "transparent"
    textColor: "{colors.text-on-dark}"
    border: "2px solid {colors.text-on-dark}"
    borderRadius: "{rounded.pill}"
    paddingX: "22px"
    fontSize: "22px"
    fontWeight: 600
    notes: "Outline pill on dark/inverted surfaces."

  button-filled-dark:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.text-on-dark}"
    borderRadius: "{rounded.circle}"
    border: "1px solid {colors.primary}"
    fontSize: "22px"
    fontWeight: 400
    notes: "Dark filled circle. Used for hamburger/icon CTAs."

  button-cta-blue:
    backgroundColor: "{colors.accent-primary}"
    textColor: "{colors.text-on-accent-blue}"
    borderRadius: "{rounded.lg}"
    border: "2px solid {colors.accent-primary}"
    fontSize: "30px"
    fontWeight: 400
    notes: "Blue arrow circle (↗). On Digital Experience card. Never mixed with lime in same section."

  button-cta-lime:
    backgroundColor: "{colors.accent-secondary}"
    textColor: "{colors.text-on-accent-lime}"
    borderRadius: "{rounded.lg}"
    border: "2px solid {colors.accent-secondary}"
    fontSize: "30px"
    fontWeight: 400
    notes: "Lime arrow circle (↗). On Content & Communication card. Never mixed with blue in same section."

  tag:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    border: "1px solid {colors.border}"
    borderRadius: "{rounded.circle}"
    fontFamily: "{typography.label.fontFamily}"
    fontSize: "{typography.label.fontSize}"
    fontWeight: "{typography.label.fontWeight}"
    letterSpacing: "{typography.label.letterSpacing}"
    textTransform: "{typography.label.textTransform}"
    paddingX: "14px"
    paddingY: "6px"
    notes: >
      Outline pill. Transparent fill. Inverts to white border + white text on dark surfaces.
      Never filled. Never accent-colored. Max 6 per card.

  card-light:
    backgroundColor: "{colors.surface-light}"
    borderRadius: "{rounded.md}"
    padding: "50px"
    notes: "Default capability card. No shadow — elevation from white vs warm background contrast."

  card-dark:
    backgroundColor: "{colors.surface-dark}"
    borderRadius: "{rounded.md}"
    textColor: "{colors.text-on-dark}"
    padding: "50px"
    notes: "Inverted card. Alternates with light cards in capabilities grid."

  card-accent-blue:
    backgroundColor: "{colors.accent-primary}"
    borderRadius: "{rounded.md}"
    textColor: "{colors.text-on-accent-blue}"
    padding: "50px"
    notes: "Stat card. Blue background. Used for '50+ Brands' counter."

  card-accent-lime:
    backgroundColor: "{colors.accent-secondary}"
    borderRadius: "{rounded.md}"
    textColor: "{colors.text-on-accent-lime}"
    padding: "50px"
    notes: "Stat card. Lime background. Used for '2+ Principals' counter."

  nav:
    backgroundColor: "{colors.background}"
    textColor: "{colors.primary}"
    notes: >
      Logo left. Right: outline pill CTA + dark circle hamburger.
      No border, no shadow. Continuous with page background.
---

## Overview

BNM Studio is a Strategic Design Studio based in Mexico City.

The visual system is built around **bold typography and restrained color**.
The typeface — Funnel Display — carries the entire personality of the brand at large scales.
Color is sparse and intentional: a warm off-white canvas, near-black type, and two accent colors
used at different frequencies.

The reference feeling: an editorial publication that also builds products.
Considered, confident, and direct — never decorative for decoration's sake.

**The two-font rule:** `Funnel Display` for all headings and display type.
`Funnel Sans` (weight 300) for all body copy and UI labels.
Never substitute with Inter, Roboto, or system fonts — Funnel is the brand.

**The accent hierarchy:**
- `#3244DD` (blue) is the primary interactive accent — CTAs, active states, key highlights.
- `#D8EF5B` (lime) is the secondary accent — complementary, one use per section.
- On dark surfaces, lime becomes the primary accent (see `accent-rgb-dark`).
- Never use both accents in the same visible screen section.

**The spacing discipline:** All spacing derives from the `36px` base unit.
Use multiples: 36, 72, 108, 144. Arbitrary values break the rhythm.

**The tone test:** Before shipping any UI, ask — does this feel like something
Diego and José would produce for a client? If yes, proceed.
If it looks like a SaaS template or default Tailwind: stop and simplify.

---

## Colors

The palette is a high-contrast warm neutral system with two accent colors.

**Background (`#F9F6F5`)** — Warm off-white. Every page lives on this.
Not pure white — the warmth softens near-black type without reducing legibility.
Never use as a card surface — reserve `#FFFFFF` for that.

**Primary (`#252525`)** — Near-black. This is where the brand lives.
Headlines, body copy, borders, buttons on light surfaces.
Not pure black — aligned in temperature with the background.

**Muted (`#666666`)** — Supporting information only.
Captions, secondary descriptions, metadata.
Never for primary copy, headings, or anything that must be read first.

**Accent Primary (`#3244DD`)** — Electric blue. The main interactive signal.
CTA circle buttons, active states, key highlights.
High contrast on light and dark surfaces alike.

**Accent Secondary (`#D8EF5B`)** — Lime green.
Hero headline highlight backgrounds, stat card fill, secondary CTA circles.
Text on lime is always `#252525` — never white (contrast fails).
One appearance per screen section, maximum.

**Surface Dark (`#161616`)** — Inverted card and section backgrounds.
Slightly lighter than pure black — softer at large scale.
On dark surfaces, lime (`#D8EF5B`) replaces blue as the accent color.

---

## Typography

Funnel Display defines the brand. At 140px, weight 600, -0.6px letter-spacing,
it is the most recognizable element of BNM Studio's visual identity.

The split between **Funnel Display** (headings) and **Funnel Sans weight 300** (body)
creates clear hierarchy through form and weight contrast — not just size.

**Rules:**
- Display headlines are tight by design (lineHeight = fontSize at 140px). Never apply default browser line-height to large type.
- Body copy (Funnel Sans, weight 300) is deliberately light. The 600↔300 contrast is intentional.
- Stat numbers (50+, 80%, 9+) use display scale. They are typographic objects.
- Use Funnel Display only at `36px` and above. Below that, use Funnel Sans.
- Never use Funnel Display for body copy — the light weight of Funnel Sans is the counterpart that makes the system work.
- Web font loading: include `font-display: swap` and preload the Display variant.

---

## Layout

All spacing is a multiple of `36px`. This is the single most important layout rule.

**Grid:** 12-column desktop (Bootstrap), 4-column mobile.
**Max content width:** `1400px`.
**Section padding:** `90–110px` vertical desktop. `64px` mobile.

**Card grid:** Asymmetric bento pattern — cards vary in size (1 or 2 columns).
Do not normalize all cards to the same dimensions.

**Depth through imagery:** 3D rendered objects cross card boundaries deliberately.
This creates spatial depth without shadow-heavy UI. Never clip imagery to card bounds.

**Responsive:**
- `< 640px`: Single column, stacked, font sizes ~80% of desktop.
- `640–1024px`: 2 columns where appropriate.
- `> 1440px`: Content centered inside max-width container.
- Touch targets: minimum `44×44px`.

---

## Elevation & Depth

No box shadows on cards. Depth is created through surface color contrast:

1. **Background** (`#F9F6F5`) — page plane.
2. **Light cards** (`#FFFFFF`) — lifted by contrast.
3. **Dark cards** (`#161616`) — grounded and heavy.
4. **Accent cards** (`#3244DD` or `#D8EF5B`) — pop by saturation.

Animation easing `cubic-bezier(0.23, 0.65, 0.74, 1.09)` has a slight overshoot.
Use for all hover states and transitions — never `ease-in-out` or `linear`.

---

## Shapes

**Card radius: `26px`** — The site's defining shape. All standard cards use this exactly.

**CTA circles:** `42–50px` radius. Arrow (↗) buttons on capability cards.
Always positioned corner (top-right or bottom-right). Never centered, never full-width.
Blue or lime fill depending on card context. This is a visual signature — maintain it exactly.

**Pill buttons:** `28px` radius. Nav CTA and secondary actions.

**Tags:** Full pill (`99px`). Always outline, never filled.

No organic or free-form shapes in the UI layer — those exist only in the 3D imagery.

---

## Components

### Navigation
Logo left (mark + wordmark). Right: `Say Hello ↗` outline pill + dark filled circle (hamburger).
Background `#F9F6F5`, no border, no shadow. Continuous with the page.

### Capability Card
`[Funnel Display h2] + [outline tags row] + [Funnel Sans 300 body] + [3D object] + [CTA circle ↗ corner]`
Cards alternate light (`#FFFFFF`) ↔ dark (`#161616`) through the grid.
3D object may overlap the card boundary — do not clip.

### Tag
Outline pill. Transparent fill. `#252525` border/text on light. White border/text on dark.
Always uppercase, tracked. Max 6 per card.

### Stat Block
Display-scale number + Funnel Sans 300 caption below.
Lives inside colored card or directly on page background.
The number dominates — everything else is secondary.

### Hero Headline
Funnel Display 140px/600. Lime block (`#D8EF5B`) behind accent word(s).
3D objects floating over the text — not clipped, not constrained.
This controlled overlap is the hero's signature. Do not clean it up.

---

## Do's and Don'ts

| ✅ Do | 🚫 Don't |
|---|---|
| Use `Funnel Display` for all headings | Substitute with Inter, Roboto, or system fonts |
| Use `Funnel Sans` weight 300 for body | Use weight 400 — it breaks the 600↔300 contrast |
| Space in multiples of `36px` | Use arbitrary spacing values |
| Use `#3244DD` for primary interactive CTAs | Use lime for primary interactive elements |
| Use lime once per section as secondary accent | Scatter lime across all interactive elements |
| Alternate light/dark cards in capabilities grid | Use same surface for all cards |
| Let 3D objects cross card boundaries | Clip imagery to card bounds |
| Apply `cubic-bezier(0.23, 0.65, 0.74, 1.09)` | Use `ease-in-out` — too generic |
| Use `#252525` for all primary text | Use pure `#000000` — too harsh against `#F9F6F5` |
| Use `#666666` for muted/secondary text only | Use muted for anything the user reads first |
| Invert tags to white on dark card surfaces | Use same tag style on both light and dark cards |

---

## Agent Prompt Guide

### Quick Token Reference

```
Background:    #F9F6F5
Surface light: #FFFFFF
Surface dark:  #161616
Text:          #252525
Muted:         #666666
Accent blue:   #3244DD   ← primary CTA / interactive
Accent lime:   #D8EF5B   ← secondary, one per section
Border:        #252525
Heading font:  'Funnel Display', weight 600, -0.6px tracking
Body font:     'Funnel Sans', weight 300
Base spacing:  36px (use multiples only)
Card radius:   26px
Easing:        cubic-bezier(0.23, 0.65, 0.74, 1.09)
```

### Example Prompts

1. "Hero: `#F9F6F5` bg, `Funnel Display` 140px/600 in `#252525`, accent word with `#D8EF5B` highlight block, 3D object overlapping the type."

2. "Light capability card: `#FFFFFF` surface, `26px` radius, 50px padding, `Funnel Display` 70px heading, `Funnel Sans` 300 body, outline tags, `#3244DD` circle CTA ↗ top-right."

3. "Dark capability card: `#161616` bg, white Funnel Display 70px heading, white outline tags, `#D8EF5B` circle CTA ↗."

4. "Stat card: `#3244DD` bg, `Funnel Display` 140px '50+' in white, `Funnel Sans` 300 caption, `26px` radius."

5. "Nav: `#F9F6F5` bg, logo left, right: `Say Hello ↗` outline pill (`28px` radius, `#252525` border) + dark filled circle hamburger."
