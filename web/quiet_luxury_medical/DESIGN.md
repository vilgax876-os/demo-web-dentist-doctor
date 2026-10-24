---
name: Quiet Luxury Medical
colors:
  surface: '#f9f9ff'
  surface-dim: '#d0daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee9fd'
  surface-container-highest: '#d9e3f7'
  on-surface: '#121c2b'
  on-surface-variant: '#44474d'
  inverse-surface: '#273140'
  inverse-on-surface: '#ebf1ff'
  outline: '#75777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#4d5f7d'
  primary: '#000615'
  on-primary: '#ffffff'
  primary-container: '#0b1f3a'
  on-primary-container: '#7587a7'
  inverse-primary: '#b5c7ea'
  secondary: '#755a23'
  on-secondary: '#ffffff'
  secondary-container: '#fed894'
  on-secondary-container: '#785c26'
  tertiary: '#03070a'
  on-tertiary: '#ffffff'
  tertiary-container: '#1a2024'
  on-tertiary-container: '#81878c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b5c7ea'
  on-primary-fixed: '#071c36'
  on-primary-fixed-variant: '#364764'
  secondary-fixed: '#ffdea6'
  secondary-fixed-dim: '#e6c180'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5b430d'
  tertiary-fixed: '#dde3e8'
  tertiary-fixed-dim: '#c1c7cc'
  on-tertiary-fixed: '#161c20'
  on-tertiary-fixed-variant: '#41484c'
  background: '#f9f9ff'
  on-background: '#121c2b'
  surface-variant: '#d9e3f7'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 56px
    fontWeight: '500'
    lineHeight: 64px
    letterSpacing: -0.01em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 36px
    fontWeight: '500'
    lineHeight: 44px
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-md:
    fontFamily: EB Garamond
    fontSize: 30px
    fontWeight: '500'
    lineHeight: 38px
  headline-sm:
    fontFamily: EB Garamond
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  body-lg:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.12em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 3rem
  margin-sm: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a quiet luxury aesthetic tailored for an elite dental and family clinic. It pairs classical prestige with clinical precision, projecting calm reassurance, uncompromising hygiene, and bespoke medical care.

The emotional tone balances the warmth of high-end hospitality with the rigorous clarity of medical excellence. The interface emphasizes expansive breathing room, delicate borders, deliberate typographic hierarchy, and understated metallic accents.

- **Design Philosophy:** Understated elegance, airy compositions, and pristine clinical legibility.
- **Visual Weight:** Light, balanced, and serene.
- **Key Characteristics:** Generous margins, subtle hairline rules, classical editorial serifs, and utilitarian sans-serif body text.

## Colors

The palette communicates permanence, trust, and refined care. 

- **Primary (`#0B1F3A` - Deep Navy):** The core anchor for primary actions, prominent titles, and brand landmarks.
- **Secondary (`#B8975A` - Champagne Gold):** Used sparingly for badges, selected states, verified indicators, and subtle decorative accents.
- **Tertiary (`#E8EEF3` - Soft Mist):** Serves as a soothing, cool background fill for cards, subtle alerts, and clinical data panels.
- **Neutral (`#1A2433` - Deep Ink):** Provides deep, accessible contrast for high-density body copy, clinical readings, and structured data tables.
- **Surfaces (`#FAF7F2` - Warm Ivory, `#FFFFFF` - Pure White):** `#FAF7F2` delivers a warm, welcoming foundation for canvas backgrounds, while `#FFFFFF` defines clean, sterile card elevations.

## Typography

The type system pairs classical editorial elegance with utilitarian clarity.

- **Headlines (EB Garamond):** Used across hero sections, treatment titles, doctor credentials, and philosophical headers. Weights are restrained to 500 and 600, delivering a graceful, unhurried reading cadence.
- **Body & Clinical Records (Inter):** Neutral, crisp, and legible at small sizes. Used for appointment overviews, patient charting, care instructions, and transactional forms.
- **Labels & Overlines (Inter):** Rendered in uppercase with tracking between `0.08em` and `0.12em` to organize clinical sections with quiet authority.

## Layout & Spacing

A 12-column responsive layout provides architectural rigor across desktop experiences, collapsing to 6 columns on tablet, and 4 columns on mobile viewports.

- **Rhythm:** Generous macro-spacing frames content to evoke calm and deliberation. Outer margins reach `3rem` on desktop screens, paired with a `1.5rem` gutter.
- **Micro-spacing:** Internal component layouts maintain consistent density. Input controls, cards, and list elements rely on `space-sm` (`0.5rem`) and `space-md` (`1rem`) to keep clinical details clean, legible, and easy to parse.

## Elevation & Depth

Visual depth is achieved through delicate surface stacking and whisper shadows rather than heavy drop-shadows or high-contrast separation.

- **Base Surfaces:** Canvas background rests at `#FAF7F2`. Elevated surfaces use pure white (`#FFFFFF`) to establish clinical cleanliness.
- **Whisper Shadows:** For hovering states and floating modals, use soft, diffused ambient light: `0 4px 20px -2px rgba(11, 31, 58, 0.04), 0 2px 6px -1px rgba(11, 31, 58, 0.02)`.
- **Delicate Hairlines:** Interfaces rely predominantly on 1px borders colored in `rgba(11, 31, 58, 0.08)` or champagne gold tints `rgba(184, 151, 90, 0.25)` to delineate boundaries cleanly without visual clutter.

## Shapes

The interface embraces a tailored soft geometry (`roundedness: 1`).

- **Containers & Cards:** Radii are held tight at `0.25rem` (4px) to `0.5rem` (8px), maintaining an architectural, clinical feel.
- **Form Controls:** Input fields and standard buttons use `0.25rem` (4px) corners for crisp alignment.
- **Accents & Pills:** Status badges, chip components, and tertiary toggles may take full `rounded-full` contours when highlighting transient clinical states or doctor availability.

## Components

### Buttons
- **Primary:** Deep navy (`#0B1F3A`) background, pure white (`#FFFFFF`) text, `0.25rem` border radius, padding `0.75rem 1.5rem`. Hover state subtle brightness shift with minimal whisper shadow.
- **Secondary (Luxury Accent):** Transparent background, 1px champagne gold border (`#B8975A`), text in deep navy (`#0B1F3A`).
- **Ghost:** Deep navy text, no background, underline or subtle highlight on hover.

### Cards & Medical Panes
- Background pure white (`#FFFFFF`) resting over warm ivory (`#FAF7F2`).
- 1px hairline border (`rgba(11, 31, 58, 0.08)`).
- Padding set to `1.5rem` to `2rem` to encourage generous whitespace around treatment breakdowns and physician profiles.

### Inputs & Selectors
- Background: `#FFFFFF` or `#FAF7F2`.
- Border: 1px solid `rgba(11, 31, 58, 0.16)`. Focus state: 1px solid `#B8975A` with subtle box-shadow ring `rgba(184, 151, 90, 0.15)`.
- Labels positioned above in `label-sm` uppercase styling.

### Badges & Status Chips
- Pill contours (`rounded-full`), padding `0.25rem 0.75rem`.
- Subtle backgrounds: Mist (`#E8EEF3`) for diagnostic details, champagne gold wash (`rgba(184, 151, 90, 0.12)`) for VIP/priority appointments. Text styled with `label-md`.

### Appointment Timelines & Doctor Profiles
- Hairline dividers in `rgba(11, 31, 58, 0.06)`.
- Left-aligned serif headings paired with clean sans-serif schedule slots.