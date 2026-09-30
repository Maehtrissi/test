---
name: Sponti Platform Hub
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#3d4947'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#6d7a77'
  outline-variant: '#bcc9c6'
  surface-tint: '#006a61'
  primary: '#00685f'
  on-primary: '#ffffff'
  primary-container: '#008378'
  on-primary-container: '#f4fffc'
  inverse-primary: '#6bd8cb'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fd'
  on-secondary-container: '#57657b'
  tertiary: '#006947'
  on-tertiary: '#ffffff'
  tertiary-container: '#00855b'
  on-tertiary-container: '#f5fff6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#89f5e7'
  primary-fixed-dim: '#6bd8cb'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#005049'
  secondary-fixed: '#d5e3fd'
  secondary-fixed-dim: '#b9c7e0'
  on-secondary-fixed: '#0d1c2f'
  on-secondary-fixed-variant: '#3a485c'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
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
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
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
    lineHeight: 16px
    letterSpacing: 0.005em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system embodies the intersection of spontaneous consumer activity and reliable B2B partner orchestration. The visual tone is active, trustworthy, and modern—balancing the energetic impulse of spontaneous gatherings with the precision, structure, and operational clarity demanded by business operators.

The aesthetic fuses **Corporate / Modern** discipline with **Minimalist** clarity:
- Clean white canvases paired with cool, grounding slate grays establish high-utility structure.
- Dynamic emerald and teal accents inject energy, signaling vitality and immediate action without descending into playfulness or gamified noise.
- Visual noise is strictly suppressed. Contrast is achieved through precise typographic weight hierarchies, crisp borders, and dedicated operational status indicators.

## Colors

The palette establishes an operational foundation with strategic high-chroma signals for live and partner-driven content.

- **Primary (`#0D9488` - Deep Teal):** Used for key interactive targets, navigation anchors, primary buttons, and selected tabs. Delivers professional confidence with a distinctive modern tint.
- **Secondary (`#334155` - Slate):** Anchors headers, data labels, table chrome, and secondary structural actions. Provides weight and high contrast without the stark harshness of pure black.
- **Tertiary (`#10B981` - Vivid Emerald):** Denotes active status, positive metric deltas, confirmed spots, and live engagement indicators.
- **Neutral (`#64748B` - Cool Slate):** Governs secondary textual information, subtle dividers, inactive tabs, and meta tags.

### Semantic Status Badges
Status indicators must strictly retain reserved tokens to prevent operational ambiguity:
- **Aktiv / Live:** Emerald background tint (`#ECFDF5`) paired with emerald text (`#047857`) and border (`#A7F3D0`).
- **In Prüfung / Under Review:** Warm Amber tint (`#FFFBEB`) with amber text (`#B45309`) and border (`#FDE68A`).
- **Partner:** Slate tint (`#F1F5F9`) with slate text (`#1E293B`) and crisp border (`#CBD5E1`).
- **Verifiziert:** Teal tint (`#F0FDFA`) with teal text (`#0F766E`) and border (`#99F6E4`).

## Typography

The design system relies entirely on `Inter` for exceptional vertical metrics, high-density legibility, and tabular numeral precision.

- **KPI Numerical Displays:** Utilize `font-variant-numeric: tabular-nums;` to prevent layout reflow during live counter updates and real-time activity metrics.
- **Hierarchical Density:** Section titles in operational tables and widgets maintain a strict `title-md` (`16px / 600`) weight to anchor modules without overwhelming table row contents.
- **Micro-labels and Indicators:** Badge text, table column headers, and partner role tags default to `label-sm` with slight uppercase tracking (`+0.03em`) for immediate scannability.

## Layout & Spacing

The layout model uses a multi-tiered responsive grid built for information-dense operational dashboards:

- **Desktop (1200px+):** Fixed persistent sidebar navigation (260px) paired with a 12-column fluid grid. Column gutters stay fixed at `1rem`, with canvas outer margins at `2rem`.
- **Tablet (768px - 1199px):** Collapsed icon-only rail (72px) paired with an 8-column layout. Gutters compress to `1rem` and canvas margins to `1.5rem`.
- **Mobile (< 768px):** Single-column stack with top header and optional bottom bar navigation. Grid collapses to 4 columns with `gutter-mobile` (`0.75rem`) and `margin-mobile` (`1rem`).

Data density follows an 8-point rhythmic scale. Vertical rhythm inside modular cards is standardized to `space-md` (`1rem`) internal padding for standard data sets and `space-sm` (`0.5rem`) for compact high-volume table rows.

## Elevation & Depth

Visual depth is achieved through **low-contrast outlines** paired with **ambient surface layers**, discarding aggressive drop shadows in favor of a clean, technical SaaS presence:

- **Base Layer (Canvas):** Set to `#F8FAFC`. All primary content areas contrast directly against this muted substrate.
- **Surface Layer (Cards, Tables, Panels):** Pure white (`#FFFFFF`) with a continuous `1px` structural outline in `#E2E8F0`. No shadow is applied under default state.
- **Interactive Hover State:** Elements elevate subtly with a micro-shadow: `0 4px 12px -2px rgba(15, 23, 42, 0.06), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`, retaining the 1px `#CBD5E1` border boundary.
- **Overlays & Modals:** Floating flyouts and dialogue modals utilize an ambient shadow: `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.06)`, framed by a crisp `#E2E8F0` border.

## Shapes

The design system adopts a balanced, refined geometry:
- **Base Components:** Standard inputs, buttons, filter dropdowns, and cards use `0.5rem` (8px) corner radius.
- **Containers & KPI Modules:** Large panels, modal dialogs, and activity containers implement `rounded-lg` (`1rem` / 16px).
- **Status Badges & Pill Filters:** Metadata tags and state indicators use fully rounded pill geometries (`9999px`) to visually differentiate metadata from actionable rectangular form elements.

## Components

### Buttons
- **Primary:** Teal fill (`#0D9488`), white text, 8px radius, height: 40px (desktop) / 36px (compact table action). Hover state shifts to `#0F766E`. Active: `#115E59`.
- **Secondary:** White background with 1px `#CBD5E1` border, Slate text (`#334155`). Hover introduces `#F8FAFC` surface fill and `#94A3B8` border.
- **Ghost/Tertiary:** No border, transparent background, text color `#475569`. Hover triggers `#F1F5F9`.

### Badges & Status Tags
- **Structure:** 6px vertical padding, 10px horizontal padding, pill-shaped geometry, uppercase `label-sm` font.
- **Dot Indicator:** Status badges contain a 6px circular dot preceding the label, styled with the status's parent primary chroma (e.g., active emerald dot `#10B981`).

### Data Tables
- **Header:** Sticky header row on `#F8FAFC`, uppercase `label-sm` slate text (`#64748B`), bottom border 1px `#E2E8F0`.
- **Rows:** Alternating transparent and `#FFFFFF` background. Hover triggers background change to `#F1F5F9`. Height: 48px standard, 40px compact.
- **Cells:** Tabular numbers aligned right, text content aligned left, badges centered or left-aligned with icon pairing.

### Input Fields & Filter Controls
- **Text Inputs:** White background, 1px border `#CBD5E1`, text `#0F172A`, placeholder `#94A3B8`. Focused state: 1px border `#0D9488` with a 3px ring in `rgba(13, 148, 136, 0.15)`.
- **Filter Groups:** Combined dropdown buttons displaying active filter count in an inline pill. Clear-all icon triggers when filters are active.

### KPI & Metric Cards
- **Structure:** Surface white, 1px border `#E2E8F0`, 16px inner padding.
- **Content Flow:** Top label (`label-md` in `#64748B`), center big numerical indicator (`headline-lg`), bottom delta row displaying trend percentage in Tertiary Emerald (`#10B981`) or Alert Coral (`#EF4444`) alongside reference period text.

### Selection Controls (Checkboxes & Radios)
- **Checkboxes:** 18px square with 4px border radius. Inactive: `#FFFFFF` with 1.5px border `#CBD5E1`. Checked: Fill `#0D9488` with a white checkmark.
- **Radios:** 18px circular with matching active teal dot inset.