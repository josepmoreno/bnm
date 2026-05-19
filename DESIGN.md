---
version: "alpha"
name: BNM Studio
description: "Strategic Design Studio. Mexico City. Full creative coverage for growing companies — branding, motion, web, and strategy under one roof. Two principals. No intermediaries. Senior work, always."

colors:
  primary: "#252525"
  background: "#F9F6F5"
  surface-light: "#FFFFFF"
  surface-dark: "#161616"
  surface-black: "#000000"
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
  xs: "20px"
  sm: "36px"
  md: "72px"
  lg: "108px"
  xl: "144px"
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
  full: "99px"

components:
  button-outline:
    backgroundColor: "{colors.surface-light}"
    textColor: "{colors.primary}"
    rounded: "{rounded.pill}"
    padding: "12px 22px"
    typography: "label"
  button-outline-dark:
    backgroundColor: "transparent"
    textColor: "{colors.text-on-dark}"
    rounded: "{rounded.pill}"
    padding: "12px 22px"
    typography: "label"
  button-cta-blue:
    backgroundColor: "{colors.accent-primary}"
    textColor: "{colors.text-on-accent-blue}"
    rounded: "{rounded.lg}"
    size: "52px"
  button-cta-lime:
    backgroundColor: "{colors.accent-secondary}"
    textColor: "{colors.text-on-accent-lime}"
    rounded: "{rounded.lg}"
    size: "52px"
  button-hamburger:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.text-on-dark}"
    rounded: "{rounded.full}"
    size: "44px"
  tag:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    padding: "6px 14px"
    typography: "label"
  tag-dark:
    backgroundColor: "transparent"
    textColor: "{colors.text-on-dark}"
    rounded: "{rounded.full}"
    padding: "6px 14px"
    typography: "label"
  card-light:
    backgroundColor: "{colors.surface-light}"
    rounded: "{rounded.md}"
    padding: "{spacing.card-lg}"
  card-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.text-on-dark}"
    rounded: "{rounded.md}"
    padding: "{spacing.card-lg}"
  card-accent-blue:
    backgroundColor: "{colors.accent-primary}"
    textColor: "{colors.text-on-accent-blue}"
    rounded: "{rounded.md}"
    padding: "{spacing.card-lg}"
  card-accent-lime:
    backgroundColor: "{colors.accent-secondary}"
    textColor: "{colors.text-on-accent-lime}"
    rounded: "{rounded.md}"
    padding: "{spacing.card-lg}"
  nav:
    backgroundColor: "{colors.background}"
    textColor: "{colors.primary}"
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

**Primary (`#252525`)** — Near-black. Headlines, body copy, borders, buttons on light surfaces. Not pure black — aligned in temperature with the warm background.

**Background (`#F9F6F5`)** — Warm off-white. Every page lives on this. Not pure white — the warmth softens near-black type without reducing legibility. Never use as a card surface — reserve `surface-light` for that.

**Muted (`#666666`)** — Supporting information only: captions, secondary descriptions, metadata. Never for primary copy, headings, or anything that must be read first.

**Accent Primary (`#3244DD`)** — Electric blue. The main interactive signal. CTA circle buttons, active states, key highlights. High contrast on light and dark surfaces alike.

**Accent Secondary (`#D8EF5B`)** — Lime green. Hero headline highlight backgrounds, stat card fill, secondary CTA circles. Text on lime is always `#252525` — never white (contrast fails). One appearance per screen section, maximum.

**Surface Dark (`#161616`)** — Inverted card and section backgrounds. Slightly lighter than pure black. On dark surfaces, lime replaces blue as the accent color.

## Typography

Funnel Display defines the brand. At 140px, weight 600, -0.6px letter-spacing, it is the most recognizable element of BNM Studio's visual identity.

The split between **Funnel Display** (headings) and **Funnel Sans weight 300** (body) creates clear hierarchy through form and weight contrast — not just size.

**Rules:**
- Display headlines are tight by design (`lineHeight = fontSize` at 140px). Never apply default browser line-height to large type.
- Body copy (Funnel Sans, weight 300) is deliberately light. The 600-to-300 weight contrast is intentional — do not use weight 400 for body.
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
- Touch targets: minimum 44×44px.

## Rounded

The shape language is rounded and controlled — never organic.

**`md` (26px)** — The site's defining shape. All standard cards use this exactly. Never mix radii within the same card grid section.

**`lg` (42px)** — CTA circle buttons (the arrow ↗ buttons on capability cards). Always positioned in a corner — top-right or bottom-right. Never centered or full-width. Blue (`#3244DD`) or lime (`#D8EF5B`) fill depending on card context. This is a visual signature — maintain it exactly.

**`pill` (28px)** — Nav CTA and secondary pill buttons.

**`full` (99px)** — Tags and icon buttons (hamburger). Always outline for tags, never filled.

No organic or free-form shapes in the UI layer — those exist only in the 3D rendered imagery.

## Components

### Navigation
Logo left (mark + wordmark). Right: `Say Hello ↗` outline pill (`button-outline`) + dark filled circle (`button-hamburger`). Background matches page (`background` token), no border, no shadow — continuous with the page.

### Capability Card
Structure: `[Funnel Display h2]` + `[tag row]` + `[Funnel Sans 300 body]` + `[3D object]` + `[CTA circle ↗ corner]`. Cards alternate `card-light` and `card-dark` through the grid. Tags use `tag` on light cards, `tag-dark` on dark cards. The 3D object may overlap the card boundary — do not clip.

### Tag
Outline pill. Transparent fill. Uses `{colors.primary}` border and text on light surfaces (`tag`). Inverts to `{colors.text-on-dark}` on dark surfaces (`tag-dark`). Always uppercase, tracked. Max 6 per card.

### Stat Block
Display-scale number (`stat` typography) + Funnel Sans 300 caption below. Lives inside `card-accent-blue`, `card-accent-lime`, `card-dark`, or directly on the page background. The number dominates — everything else is secondary.

### Hero Headline
`display` typography, `{colors.primary}` text. Accent word(s) receive a `{colors.accent-secondary}` background block. 3D objects float over the text — not clipped, not constrained. This controlled overlap is the hero's signature. Do not clean it up.

## Do's and Don'ts

- Do: Use `Funnel Display` for all headings
- Do: Use `Funnel Sans` weight 300 for body copy
- Do: Space in multiples of `36px`
- Do: Use `{colors.accent-primary}` for primary interactive CTAs
- Do: Use `{colors.accent-secondary}` once per section as secondary accent
- Do: Alternate `card-light` and `card-dark` in the capabilities grid
- Do: Let 3D objects cross card boundaries
- Do: Apply `cubic-bezier(0.23, 0.65, 0.74, 1.09)` to all transitions (0.3s medium, 0.1s fast)
- Do: Use `{colors.primary}` for all primary text
- Do: Use `{colors.muted}` for secondary text only
- Don't: Substitute Funnel with Inter, Roboto, or system fonts
- Don't: Use Funnel Sans weight 400 for body — breaks the 600-to-300 contrast
- Don't: Use arbitrary spacing values outside the 36px scale
- Don't: Use `{colors.accent-secondary}` for primary interactive elements
- Don't: Show both accent colors in the same visible screen section
- Don't: Normalize all capability cards to the same size
- Don't: Clip 3D imagery to card bounds
- Don't: Use `ease-in-out` for transitions — too generic
- Don't: Use pure `#000000` for text — too harsh against `{colors.background}`
- Don't: Use `{colors.muted}` for anything the user must read first
