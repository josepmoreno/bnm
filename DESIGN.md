---
name: BNM Studio
version: "1.1"
description: "Strategic Design Studio. Mexico City. Full creative coverage for growing companies — branding, motion, web, and strategy under one roof. Two principals. No intermediaries. Senior work, always."

colors:
  background: "#F9F6F5"
  surface-light: "#FFFFFF"
  surface-dark: "#161616"
  surface-black: "#000000"
  primary: "#252525"
  muted: "#666666"
  border: "#252525"
  accent-primary: "#3244DD"
  accent-secondary: "#D8EF5B"
  text-on-dark: "#FFFFFF"
  text-on-accent-blue: "#FFFFFF"
  text-on-accent-lime: "#252525"

typography:
  display:
    fontFamily: "'Funnel Display', sans-serif"
    fontSize: "140px"
    fontWeight: "600"
    lineHeight: "140px"
    letterSpacing: "-0.6px"
  h1:
    fontFamily: "'Funnel Display', sans-serif"
    fontSize: "120px"
    fontWeight: "600"
    lineHeight: "126px"
    letterSpacing: "-0.6px"
  h2:
    fontFamily: "'Funnel Display', sans-serif"
    fontSize: "70px"
    fontWeight: "600"
    lineHeight: "77px"
    letterSpacing: "-0.6px"
  h3:
    fontFamily: "'Funnel Display', sans-serif"
    fontSize: "36px"
    fontWeight: "600"
    lineHeight: "43px"
    letterSpacing: "0px"
  body-lg:
    fontFamily: "'Funnel Sans', sans-serif"
    fontSize: "22px"
    fontWeight: "300"
    lineHeight: "35px"
    letterSpacing: "0px"
  body-md:
    fontFamily: "'Funnel Sans', sans-serif"
    fontSize: "18px"
    fontWeight: "300"
    lineHeight: "29px"
    letterSpacing: "0px"
  label:
    fontFamily: "'Funnel Sans', sans-serif"
    fontSize: "14px"
    fontWeight: "500"
    lineHeight: "20px"
    letterSpacing: "0.04em"
    textTransform: "uppercase"
  stat:
    fontFamily: "'Funnel Display', sans-serif"
    fontSize: "140px"
    fontWeight: "600"
    lineHeight: "140px"
    letterSpacing: "-0.6px"

spacing:
  base: "36px"
  1x: "36px"
  2x: "72px"
  3x: "108px"
  4x: "144px"
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
    textColor: "#252525"
    rounded: "28px"
    padding: "12px 22px"
    typography: "label"
  button-outline-dark:
    backgroundColor: "transparent"
    textColor: "#FFFFFF"
    rounded: "28px"
    padding: "12px 22px"
    typography: "label"
  button-cta-blue:
    backgroundColor: "#3244DD"
    textColor: "#FFFFFF"
    rounded: "42px"
    size: "52px"
  button-cta-lime:
    backgroundColor: "#D8EF5B"
    textColor: "#252525"
    rounded: "42px"
    size: "52px"
  button-hamburger:
    backgroundColor: "#252525"
    textColor: "#FFFFFF"
    rounded: "99px"
    size: "44px"
  tag:
    backgroundColor: "transparent"
    textColor: "#252525"
    rounded: "99px"
    padding: "6px 14px"
    typography: "label"
  card-light:
    backgroundColor: "#FFFFFF"
    rounded: "26px"
    padding: "50px"
  card-dark:
    backgroundColor: "#161616"
    textColor: "#FFFFFF"
    rounded: "26px"
    padding: "50px"
  card-accent-blue:
    backgroundColor: "#3244DD"
    textColor: "#FFFFFF"
    rounded: "26px"
    padding: "50px"
  card-accent-lime:
    backgroundColor: "#D8EF5B"
    textColor: "#252525"
    rounded: "26px"
    padding: "50px"
  nav:
    backgroundColor: "#F9F6F5"
    textColor: "#252525"
---

## Overview

BNM Studio is a Strategic Design Studio based in Mexico City.

The visual system is built around **bold typography and restrained color**. The typeface — Funnel Display — carries the entire personality of the brand at large scales. Color is sparse and intentional: a warm off-white canvas, near-black type, and two accent colors used at different frequencies.

The reference feeling: an editorial publication that also builds products. Considered, confident, and direct — never decorative for decoration's sake.

**The two-font rule:** `Funnel Display` for all headings and display type. `Funnel Sans` (weight 300) for all body copy and UI labels. Never substitute with Inter, Roboto, or system fonts — Funnel is the brand.

**The accent hierarchy:**
- `#3244DD` (blue) is the primary interactive accent — CTAs, active states, key highlights.
- `#D8EF5B` (lime) is the secondary accent — complementary, one use per section.
- On dark surfaces, lime becomes the primary accent.
- Never use both accents in the same visible screen section.

**The spacing discipline:** All spacing derives from the `36px` base unit. Use multiples: 36, 72, 108, 144. Arbitrary values break the rhythm.

**The tone test:** Before shipping any UI, ask — does this feel like something Diego and José would produce for a client? If yes, proceed. If it looks like a SaaS template or default Tailwind: stop and simplify.

## Colors

The palette is a high-contrast warm neutral system with two accent colors.

**Background (`#F9F6F5`)** — Warm off-white. Every page lives on this. Not pure white — the warmth softens near-black type without reducing legibility. Never use as a card surface — reserve `#FFFFFF` for that.

**Primary (`#252525`)** — Near-black. Headlines, body copy, borders, buttons on light surfaces. Not pure black — aligned in temperature with the background.

**Muted (`#666666`)** — Supporting information only: captions, secondary descriptions, metadata. Never for primary copy, headings, or anything that must be read first.

**Accent Primary (`#3244DD`)** — Electric blue. The main interactive signal. CTA circle buttons, active states, key highlights. High contrast on light and dark surfaces alike.

**Accent Secondary (`#D8EF5B`)** — Lime green. Hero headline highlight backgrounds, stat card fill, secondary CTA circles. Text on lime is always `#252525` — never white (contrast fails). One appearance per screen section, maximum.

**Surface Dark (`#161616`)** — Inverted card and section backgrounds. Slightly lighter than pure black. On dark surfaces, lime replaces blue as the accent color.

## Typography

Funnel Display defines the brand. At 140px, weight 600, -0.6px letter-spacing, it is the most recognizable element of BNM Studio's visual identity.

The split between **Funnel Display** (headings) and **Funnel Sans weight 300** (body) creates clear hierarchy through form and weight contrast — not just size.

**Rules:**
- Display headlines are tight by design (lineHeight = fontSize at 140px). Never apply default browser line-height to large type.
- Body copy (Funnel Sans, weight 300) is deliberately light. The 600 to 300 weight contrast is intentional — do not use weight 400 for body.
- Stat numbers (50+, 80%, 9+) use display scale. They are typographic objects, not data.
- Use Funnel Display only at `36px` and above. Below that, use Funnel Sans.
- Web font loading: include `font-display: swap` and preload the Display variant.

## Layout

All spacing is a multiple of `36px`. This is the single most important layout rule.

**Grid:** 12-column desktop (Bootstrap), 4-column mobile.
**Max content width:** `1400px`.
**Section padding:** `90–110px` vertical desktop. `64px` mobile.

**Card grid:** Asymmetric bento pattern — cards vary in size (1 or 2 columns). Do not normalize all cards to the same dimensions.

**Depth through imagery:** 3D rendered objects cross card boundaries deliberately. Never clip imagery to card bounds.

**Responsive:**
- Less than 640px: Single column, stacked, font sizes approximately 80% of desktop.
- 640–1024px: 2 columns where appropriate.
- Greater than 1440px: Content centered inside max-width container.
- Touch targets: minimum 44x44px.

## Elevation & Depth

No box shadows on cards. Depth is created through surface color contrast:

1. **Background** (`#F9F6F5`) — page plane.
2. **Light cards** (`#FFFFFF`) — lifted by contrast.
3. **Dark cards** (`#161616`) — grounded and heavy.
4. **Accent cards** (`#3244DD` or `#D8EF5B`) — pop by saturation.

Animation easing `cubic-bezier(0.23, 0.65, 0.74, 1.09)` has a slight overshoot — confident and settled, not mechanical. Use for all hover states and transitions — never `ease-in-out` or `linear`.

## Shapes

**Card radius: `26px`** — The site's defining shape. All standard cards use this exactly. Never mix radii within the same card grid section.

**CTA circles:** `42px` radius. Arrow (↗) buttons on capability cards. Always positioned corner — top-right or bottom-right. Never centered, never full-width. Blue (`#3244DD`) or lime (`#D8EF5B`) fill depending on card context. This is a visual signature — maintain it exactly.

**Pill buttons:** `28px` radius. Nav CTA and secondary actions.

**Tags:** Full pill (`99px`). Always outline, never filled.

No organic or free-form shapes in the UI layer — those exist only in the 3D imagery.

## Components

### Navigation
Logo left (mark + wordmark). Right: `Say Hello ↗` outline pill + dark filled circle (hamburger). Background `#F9F6F5`, no border, no shadow. Continuous with the page.

### Capability Card
Structure: Funnel Display h2 + outline tags row + Funnel Sans 300 body + 3D object + CTA circle ↗ corner. Cards alternate light (`#FFFFFF`) and dark (`#161616`) through the grid. 3D object may overlap the card boundary — do not clip.

### Tag
Outline pill. Transparent fill. `#252525` border and text on light surfaces. White border and text on dark surfaces. Always uppercase, tracked. Max 6 per card.

### Stat Block
Display-scale number + Funnel Sans 300 caption below. Lives inside colored card or directly on page background. The number dominates — everything else is secondary.

### Hero Headline
Funnel Display 140px, weight 600. Lime block (`#D8EF5B`) behind accent word(s). 3D objects floating over the text — not clipped, not constrained. This controlled overlap is the hero's signature. Do not clean it up.

## Do's and Don'ts

- Do: Use `Funnel Display` for all headings
- Do: Use `Funnel Sans` weight 300 for body copy
- Do: Space in multiples of `36px`
- Do: Use `#3244DD` for primary interactive CTAs
- Do: Use lime once per section as secondary accent
- Do: Alternate light and dark cards in capabilities grid
- Do: Let 3D objects cross card boundaries
- Do: Apply `cubic-bezier(0.23, 0.65, 0.74, 1.09)` to all transitions
- Do: Use `#252525` for all primary text
- Do: Use `#666666` for muted and secondary text only
- Don't: Substitute Funnel with Inter, Roboto, or system fonts
- Don't: Use Funnel Sans weight 400 for body — breaks the 600 to 300 contrast
- Don't: Use arbitrary spacing values
- Don't: Use lime for primary interactive elements
- Don't: Scatter lime across all interactive elements
- Don't: Use the same surface for all capability cards
- Don't: Clip 3D imagery to card bounds
- Don't: Use `ease-in-out` — too generic
- Don't: Use pure `#000000` for text — too harsh against `#F9F6F5`
- Don't: Use muted color for anything the user reads first

## Agent Prompt Guide

Quick token reference:

```
Background:    #F9F6F5
Surface light: #FFFFFF
Surface dark:  #161616
Text:          #252525
Muted:         #666666
Accent blue:   #3244DD   (primary CTA / interactive)
Accent lime:   #D8EF5B   (secondary, one per section)
Border:        #252525
Heading font:  Funnel Display, weight 600, -0.6px tracking
Body font:     Funnel Sans, weight 300
Base spacing:  36px (multiples only)
Card radius:   26px
Easing:        cubic-bezier(0.23, 0.65, 0.74, 1.09)
```

Example prompts:

1. Hero section: `#F9F6F5` background, Funnel Display 140px weight 600 in `#252525`, accent word with `#D8EF5B` highlight block, 3D object overlapping the type.
2. Light capability card: `#FFFFFF` surface, `26px` radius, 50px padding, Funnel Display 70px heading, Funnel Sans 300 body, outline tags, `#3244DD` circle CTA top-right.
3. Dark capability card: `#161616` background, white Funnel Display 70px heading, white outline tags, `#D8EF5B` circle CTA.
4. Stat card: `#3244DD` background, Funnel Display 140px in white, Funnel Sans 300 caption, `26px` radius.
5. Nav: `#F9F6F5` background, logo left, right: outline pill Say Hello (28px radius) + dark filled circle hamburger.
