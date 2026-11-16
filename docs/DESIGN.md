---
name: AuraClinic Clinical Aesthetic
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#404847'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#717977'
  outline-variant: '#c0c8c6'
  surface-tint: '#3c6660'
  primary: '#002421'
  on-primary: '#ffffff'
  primary-container: '#0d3b36'
  on-primary-container: '#7aa59e'
  inverse-primary: '#a3cfc8'
  secondary: '#994533'
  on-secondary: '#ffffff'
  secondary-container: '#fd947e'
  on-secondary-container: '#762b1c'
  tertiary: '#18211f'
  on-tertiary: '#ffffff'
  tertiary-container: '#2d3634'
  on-tertiary-container: '#959f9c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bfece4'
  primary-fixed-dim: '#a3cfc8'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#234e48'
  secondary-fixed: '#ffdad3'
  secondary-fixed-dim: '#ffb4a4'
  on-secondary-fixed: '#3e0500'
  on-secondary-fixed-variant: '#7a2e1f'
  tertiary-fixed: '#dbe5e2'
  tertiary-fixed-dim: '#bfc9c6'
  on-tertiary-fixed: '#141d1c'
  on-tertiary-fixed-variant: '#3f4947'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '500'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.005em
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
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies a balanced, clinical aesthetic designed for luxury medical aesthetics and dermatology. It pairs deep architectural forest teal with warm, comforting neutrals to dissolve clinical anxiety while projecting rigorous medical authority and prestige.

### Emotional Response & Personality
The UI conveys absolute precision, sterile elegance, and discreet hospitality. Interfaces must feel serene, trustworthy, and high-touch—evoking the atmosphere of a private, high-end medical sanctuary.

### Design Movement & Aesthetic
A synthesis of modern clinical minimalism and high-end editorial clarity. Layouts leverage generous structural white space, hairline structural borders, and controlled typography to maintain uncompromising legibility across both English and Arabic typographic scripts.

## Colors

The palette grounds high-stakes aesthetic and clinical choices in reassuring, organic tones:

- **Primary (`#0D3B36` - Deep Forest Teal):** Used for structural navigation (sidebars, primary headers), definitive text anchors, and authority badges. Establishes medical gravitas and visual weight.
- **Secondary (`#D97762` - Muted Terracotta / Rose Bronze):** Used intentionally for primary interactions, booking CTAs, accent lines, and focal points that require warmth and human connection.
- **Tertiary (`#E2ECE9` - Calming Soft Sage):** Used for soft status tags, gentle highlights, table headers, and passive contextual backgrounds.
- **Neutral Background (`#F7F5F0` - Warm Oatmeal):** The foundational canvas color across all full-bleed screens, softening harsh sterile whites.
- **Surface Crisp (`#FFFFFF`):** Reserved for elevated cards, forms, and clinical data surfaces to ensure pristine contrast.
- **Hairline Border (`#E5E0D8` - Warm Stone):** Defines component edges with delicate, architectural precision.

## Typography

The typographic hierarchy prioritizes crystal-clear clinical legibility, balance, and effortless bilingual adaptability (English with IBM Plex Sans Arabic fallback).

- **Headlines & Display:** Set in medium weights (`500` or `600`) to convey restraint and composure rather than aggressive heaviness. Slight negative letter-spacing maintains tight elegance at scale.
- **Body:** Engineered for patient record readouts, consent forms, and treatment plans. Generous line-height ratios prevent visual fatigue.
- **Labels & Microcopy:** Rendered with subtle positive tracking for immediate legibility in data chips, dosage metrics, and appointment timestamps.
- **Bilingual Considerations:** Vertical alignment must maintain identical baselines across English LTR and Arabic RTL views. Ensure line-height values remain uncompressed to accommodate Arabic ascenders and descenders.

## Layout & Spacing

The layout philosophy uses a structured fluid grid calibrated for clinical workstations, treatment tablets, and patient mobile views.

- **Desktop (12 columns):** `2.5rem` outer canvas margins with `1.5rem` gutters. Accommodates split views (e.g., patient dermascopic imaging alongside procedure histories).
- **Tablet (8 columns):** `2rem` margins with `1.25rem` gutters for point-of-care charting.
- **Mobile (4 columns):** `1.25rem` margins with `1rem` gutters, prioritizing stacked clinical cards and bottom-sheet drawers.
- **Rhythm:** Spacing follows an 8px architectural cadence (`0.5rem`, `1rem`, `1.5rem`, `2.5rem`), enforcing deliberate breathing room around critical medical inputs.

## Elevation & Depth

Visual hierarchy avoids heavy drop-shadows or stark visual breaks, relying instead on tonal layering and gossamer edge definition:

- **Tonal Layers:** The baseline canvas is `#F7F5F0`. Functional workspace modules, treatment tables, and consultation notes lift onto clean `#FFFFFF` cards.
- **Hairline Outlines:** All card structures, dialogs, and segmented toggles are bounded by a single `1px solid #E5E0D8` perimeter to ensure crisp structural division.
- **Ambient Diffused Shadows:** For interactive overlays, patient modals, and dropdown panels, depth is conveyed through a warm, ultra-diffused shadow tinted with forest teal: `0 8px 32px -4px rgba(13, 59, 54, 0.06), 0 2px 6px -1px rgba(13, 59, 54, 0.03)`.

## Shapes

The system relies on a controlled, subtle corner radius (`0.25rem` default, `0.5rem` for large cards/modals) that balances warmth with medical authority.

- **Soft Radii:** Avoids both sharp brutalist points and overly playful pill contours. Buttons, input fields, and clinical badges feature clean, disciplined `4px` corners.
- **Cards & Modals:** Medium containers use `8px` (`rounded-lg`) to soften expansive boundaries without sacrificing the precision of a certified clinical suite.

## Components

### Buttons
- **Primary Action (Treatment Booking, Save Clinical Note):** Background `#D97762`, text `#FFFFFF`, radius `0.25rem`. Hover state transitions to `#C66551`.
- **Secondary Authority (Print Rx, Reassign Specialist):** Background `#0D3B36`, text `#FFFFFF`.
- **Tertiary / Outline:** Background transparent, border `1px solid #E5E0D8`, text `#0D3B36`. Hover state fills with `#E2ECE9`.

### Chips & Badges
- **Status (Confirmed, Completed, Stable):** Background `#E2ECE9`, text `#0D3B36`, border `1px solid rgba(13, 59, 54, 0.12)`, radius `0.25rem`.
- **Alert / Action Required:** Soft muted peach background (`#F9EAE6`) with `#D97762` text.

### Form Inputs
- **Text Fields & Dropdowns:** Pure `#FFFFFF` background, `1px solid #E5E0D8` border, text `#0D3B36`. Focus state transitions the border to `#0D3B36` with a `2px` subtle focus halo `rgba(13, 59, 54, 0.1)`. RTL input automatically mirrors icon positioning and label alignments.

### Checkboxes & Radios
- **Control Element:** `16px` diameter with `2px` border in `#E5E0D8`. Selected state fills with `#0D3B36` displaying a white check or inner dot.

### Cards & Clinical Panels
- **Standard Card:** Crisp `#FFFFFF` surface, `1px solid #E5E0D8` border, internal padding `1.5rem` (`space-lg`), ambient diffused teal shadow on interactive hover.
- **Sidebar Panels:** Deep architectural `#0D3B36` surface, muted teal secondary text, active navigation item highlighted in warm `#D97762`.

### Specialized Clinical Components
- **Bilingual Patient Summary Bar:** Dual-directional metadata row balancing Latin and Arabic script metrics with uniform label weights.
- **Dermatology Comparison Slider:** Minimal split-screen frame bounded by a hairline border, using a `#D97762` tactile divider handle.