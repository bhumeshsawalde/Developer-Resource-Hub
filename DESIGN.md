---
name: DevResource Hub
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d8'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#918fa1'
  outline-variant: '#464555'
  surface-tint: '#c3c0ff'
  primary: '#c3c0ff'
  on-primary: '#1d00a5'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#4d44e3'
  secondary: '#adc6ff'
  on-secondary: '#002e6a'
  secondary-container: '#0566d9'
  on-secondary-container: '#e6ecff'
  tertiary: '#c0c1ff'
  on-tertiary: '#1000a9'
  tertiary-container: '#4b4dd8'
  on-tertiary-container: '#d9d8ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
  code-inline:
    fontFamily: monospace
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
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
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
The design system embodies a focused, high-utility workspace tailored for software engineers, devops practitioners, and technical architects. Its core identity balances corporate stability with modern developer aesthetics: zero visual noise, dense yet comfortable information architecture, and immediate legibility of complex hierarchical data.

Drawing from modern technical workspaces, the system uses subtle surface transitions, dark slate neutrals, and calculated indigo-to-blue accents to prioritize code, analytics, and documentation without visual exhaustion. The emotional signature is calm precision—reassuring, robust, and frictionless during long sessions of development and review.

## Colors
The palette leverages a dark-first foundation rooted in deep slate values (`#0F172A`, `#1E293B`, `#334155`), ensuring reduced eye fatigue in sustained work environments while remaining fully translatable to light mode. 

Primary actions and focal highlights utilize Indigo `#4F46E5` paired with tertiary Indigo Light `#6366F1` for interactive hover states and key active markers. Secondary Tech Blue `#3B82F6` serves informational cues, telemetry graphs, and secondary workflow milestones. Neutral borders are strictly kept to low-contrast slate steps (`#1E293B` to `#334155`) to clearly define boundaries without slicing the screen into disjointed segments.

## Typography
Typography relies on the systematic precision of Inter across all core UI layers. High-density dashboards require tight horizontal tracking at display sizes to maintain unity, while body sizes preserve standard optical spacing for immediate code readability and documentation parsing. 

Headings emphasize structural scanability via medium-to-bold weights, while labels and metadata utilize semi-bold weights at compact sizes. Monospace elements (`code-inline`) are reserved for inline commands, git hashes, package versions, and numeric metric indicators.

## Layout & Spacing
The layout follows a fluid-responsive grid system paired with strict 4px/8px modular spacing increments. Desktop layouts operate primarily on a 12-column dynamic grid with fixed max-width content frames (1440px), adapting down to an 8-column layout on tablets and a 4-column structure on mobile devices.

Panels and analytical sections utilize `space-md` (16px) for interior padding, escalating to `space-lg` (24px) for expansive card views and root module boundaries. Structural sidebars default to fixed widths with collapsible states to reserve maximum canvas space for data streams, terminal feeds, and code tables.

## Elevation & Depth
Depth is produced through subtle tonal layering and hairline borders rather than heavy drop shadows. Surfaces advance in visual space as their slate value lightens: root canvas is `#0F172A`, level-1 containers use `#1E293B`, and elevated interactive modules use `#334155`.

Shadows are muted, diffuse, and tinted by dark slate. For elevated panels or modals, a dual-layer shadow applies: a sharp 1px structural contact shadow combined with an ambient blur (`0 10px 25px -5px rgba(2, 6, 23, 0.45)`). Interactive cards apply a border transition from subtle slate (`#334155`) to highlighted indigo (`#6366F1`) on hover, providing instant feedback without layout shifts.

## Shapes
Roundedness level 2 sets a baseline of `0.5rem` (8px) for buttons, text inputs, and small controls. Structural cards, modal dialogues, and primary analytical containers scale smoothly to `rounded-xl` (`1.5rem` / 24px) or `rounded-lg` (`1rem` / 16px) depending on surface hierarchy.

Interior component corners are mathematically nested: containers with `1rem` external rounding contain children with `0.5rem` rounding to maintain equidistant border margins throughout the interface.

## Components

### Buttons
- **Primary:** Background `#4F46E5`, white text, 8px (`rounded-base`) radius. On hover, background shifts to `#6366F1`. Active state invokes a subtle inset scale down to `0.98`.
- **Secondary:** Transparent background with a 1px border of `#334155`, text in neutral-200. On hover, background fills with `#1E293B` and border lightens to `#475569`.
- **Ghost:** No border, text in neutral-300, background activates with `#1E293B` on hover.

### Inputs & Text Areas
- Background `#1E293B` with a 1px border of `#334155`. Text is light slate with placeholder values in `#64748B`. Focused inputs transition the border to `#4F46E5` accompanied by a 2px outer glow (`rgba(79, 70, 229, 0.25)`).

### Cards & Resource Modules
- Base surface `#1E293B` wrapped in a 1px `#334155` border with `rounded-lg` (16px) corners. Header areas separate cleanly with an internal bottom rule. Hoverable repository or metric cards feature an ease-out transition to a brighter border tone (`#4F46E5`).

### Chips, Tags & Badges
- Compact geometry with 4px or pill-shaped rounding. Status indicators combine a 10% opacity colored background matching the token status (Indigo, Emerald, Amber, Rose) with full-intensity text and an optional 6px circular dot indicator. Monospace metadata tags use `#0F172A` background with `#94A3B8` typography.

### Checkboxes & Radios
- Box size of 16x16px with a 1.5px border of `#475569`, transitioning to `#4F46E5` fill and white checkmark/dot upon selection. Focus states reproduce the primary focus ring token.

### Data Tables & Lists
- Minimalist zebra-striping or thin horizontal rules (`#1E293B`). Headers utilize uppercase `label-sm` with subtle sorting arrows. Rows respond with `#1E293B` background on hover. Monospace tabular numbers ensure aligned numeric comparisons.