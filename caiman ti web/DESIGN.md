---
name: Caiman Data Engine
colors:
  surface: '#111319'
  surface-dim: '#111319'
  surface-bright: '#373940'
  surface-container-lowest: '#0c0e14'
  surface-container-low: '#191b22'
  surface-container: '#1e1f26'
  surface-container-high: '#282a30'
  surface-container-highest: '#33343b'
  on-surface: '#e2e2eb'
  on-surface-variant: '#bacbb5'
  inverse-surface: '#e2e2eb'
  inverse-on-surface: '#2e3037'
  outline: '#859581'
  outline-variant: '#3c4b3a'
  surface-tint: '#1ee554'
  primary: '#47fe69'
  on-primary: '#00390d'
  primary-container: '#10e050'
  on-primary-container: '#005d1b'
  inverse-primary: '#006e22'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#ffd5c8'
  on-tertiary: '#53220f'
  tertiary-container: '#ffaf94'
  on-tertiary-container: '#7a402b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6eff7d'
  primary-fixed-dim: '#1ee554'
  on-primary-fixed: '#002105'
  on-primary-fixed-variant: '#005317'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59c'
  on-tertiary-fixed: '#380d01'
  on-tertiary-fixed-variant: '#6f3723'
  background: '#111319'
  on-background: '#e2e2eb'
  surface-variant: '#33343b'
typography:
  headline-xl:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Geist
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.005em
  label-data:
    fontFamily: Geist
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
  label-mono:
    fontFamily: Geist
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 0.75rem
  margin: 1rem
  space-xs: 0.125rem
  space-sm: 0.375rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

This design system embodies the precision, density, and computational elegance of high-tier modern data platforms. Inspired by the dense, structural clarity of advanced spreadsheet-database hybrids, the visual character strikes a balance between minimalist developer-tool utility and luxury fintech finish. 

The aesthetic is built on a dark carbon architectural canvas, prioritizing information density without visual chaos. Sub-pixel precision, delicate hairline dividers, and deliberate micro-accents of radiant green signal system health, active automation, and high-frequency data throughput. The emotional response should be one of total operational control, speed, and analytical power—treating complex multi-attribute data pipelines as an exquisite, tactile instrument.

## Colors

The palette operates on a strict functional hierarchy optimized for low visual fatigue in prolonged high-density data viewing:

- **Carbon Canvas (`#090A0F`, `#0F1117`, `#161922`):** The structural core. Deep slate-carbon foundations layered to articulate nested spreadsheet rows, flyout panels, and contextual inspectors.
- **Radiant Emerald (`#10E050`):** Reserved exclusively for successful pipeline executions, enrichment matches, active live states, and primary action affordances. Never applied as massive solid fills across broad panels; it functions as a laser-targeted beacon.
- **Electric Cyan (`#06B6D4`):** Secondary operational accent utilized for external API webhooks, dynamic formula badges, query parameters, and analytical metrics.
- **Micro Hairlines (`rgba(255, 255, 255, 0.08)` to `rgba(255, 255, 255, 0.12)`): Monolithic 1px structural outlines that define the data grid without introducing visual weight.
- **Content Hierarchy:** Text levels utilize calibrated zinc alphas (`100%` pure white for focused data cells, `70%` for standard labels, `40%` for metadata keys, and `25%` for inactive column tokens).

## Typography

The typography system relies on **Geist**, selected for its geometric rigor, neutral technical presence, and pristine rendering at ultra-compact font sizes. 

- **Scale & Density:** Font sizes pivot around a compact `13px` base (`body-md`), standard in dense tabular applications to maximize screen real estate and data visibility.
- **Tabular Figures:** Numbers and metrics enforce monospaced numeric alignment (`font-variant-numeric: tabular-nums`) across all grid elements, counters, timestamps, and row indicators.
- **Label Tracking:** Micro badges and category tags feature slight positive letter spacing (`0.02em` to `0.04em`) to ensure legibility when rendered in all-caps or small dimensions.

## Layout & Spacing

The layout embraces a modular spreadsheet-first workbench:

- **Density & Cadence:** A strict 4px sub-grid dictates spacing. Micro paddings (`space-xs` to `space-sm`) govern table cell insets and pill badges, while structural margins (`space-lg` to `space-xl`) define view docks and modal overlays.
- **Spreadsheet/Table Canvas:** Primary interactive surfaces avoid floating separated cards in favor of continuous, contiguous grid panes connected by subtle 1px dividers.
- **Bento & Drawer Paneling:** Responsive arrangements use flexible horizontal split panes that collapse gracefully. On viewports below `1024px`, side panels tuck into sliding sheets, while table views preserve horizontal panning with frozen primary ID columns.

## Elevation & Depth

Elevation is achieved strictly through tonal stacking and razor-sharp border separation rather than diffuse, heavy drop shadows:

- **Surface Tiers:**
  - **Base Canvas (`#090A0F`):** Deep background for overall app shell and viewport borders.
  - **Surface Default (`#0F1117`):** Primary grid area, spreadsheet rows, and inspector dock surfaces.
  - **Surface Raised (`#161922`):** Column headers, active selected cells, floating command bars, and dropdown menus.
  - **Surface Popover (`#1C202C`):** High-priority modals and tooltips.
- **1px Crisp Borders:** Every tier transition is defined by a 1px border line (`rgba(255, 255, 255, 0.08)`).
- **Glow Accents:** Focused data inputs and running operations cast a micro perimeter glow (`box-shadow: 0 0 0 1px #10E050, 0 0 8px rgba(16, 224, 80, 0.25)`), creating an electric, reactive feel without softening the structural edges.

## Shapes

The design system employs a disciplined, sharp shape language (`roundedness: 1`):

- **Cell & Grid Elements:** Direct 2px or 4px radiuses (`0.25rem`) that maintain rectangular visual efficiency and snug nested alignments.
- **Controls & Buttons:** Stand at standard 4px corners (`0.25rem`), keeping tools feeling industrial and precise.
- **Badges & Tags:** Slightly rounded (`4px` to `6px`) or full pill silhouettes only for isolated status dots and enrichment status badges, preserving contrast against the rigid tabular structure.

## Components

### Buttons
- **Primary:** High-radiance green (`#10E050`) background with dark carbon ink (`#090A0F`), 4px radius, weight 500, compact padding (`6px 12px`). Hover states apply subtle illumination via brightness lift without layout shift.
- **Secondary / Ghost:** Carbon surface (`#161922`) with hairline border (`rgba(255, 255, 255, 0.1)`), light text (`rgba(255, 255, 255, 0.8)`). Hover induces a white alpha flood (`rgba(255, 255, 255, 0.04)`).

### Precision Data Grid & Table Cells
- **Row Anatomy:** Fixed 32px or 36px height. Row separators use 1px solid `rgba(255, 255, 255, 0.06)`.
- **Selection State:** Active cell features a 1px inner green border (`#10E050`) with an ultra-subtle tinted fill (`rgba(16, 224, 80, 0.04)`).
- **Column Headers:** Monospaced type tone, zinc text, subtle sort arrows, and integrated hover actions (filter, group, lock).

### Chips & Micro-Badges
- **Status Pills:** Carbon-tinted backgrounds with 1px border matched to data states:
  - *Success / Enriched:* Green glow border (`rgba(16, 224, 80, 0.3)`), green text (`#10E050`), pulsing indicator dot.
  - *Webhook / Source:* Cyan glow border (`rgba(6, 182, 212, 0.3)`), cyan text (`#06B6D4`).
  - *Pending / Raw:* Neutral slate border (`rgba(255, 255, 255, 0.1)`), zinc text (`rgba(255, 255, 255, 0.6)`).

### Input Fields & Search Bars
- Compact 32px height, inset carbon background (`#0B0D13`), 1px outline (`rgba(255, 255, 255, 0.1)`). 
- Focus invokes an electric hairline highlight (`#10E050` or `#06B6D4`) and subtle outer bloom.
- Monospaced query tokens within input parameters for formulas and filtering operations.

### Checkboxes & Selection Controls
- Rectangular 14px size, 2px border radius, sharp dark fill. Checked state renders solid `#10E050` with an inverted black SVG checkmark.

### Bento Blocks & Detail Drawers
- Deep slate containers with continuous hair-thin borders. Used for record inspector panels, execution logs, and enriched metadata previews alongside the main tabular grid.