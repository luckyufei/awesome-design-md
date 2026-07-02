---
version: alpha
name: DeepBI-design-analysis
description: A flat, wireframe-analytic interface for the DeepBI data platform. The system anchors on a white canvas with a zinc-gray skeleton and blue-600 anchor accents. No shadows — all depth comes from border dividers and surface-tone shifts. Type voice runs a clean geometric sans (Inter) for all levels, with JetBrains Mono for data cells and code. The brand voltage is restrained: zinc is the structural backbone, blue is the action anchor.

colors:
  canvas: "#ffffff"
  surface-secondary: "#fafafa"
  surface-secondary-hover: "#f4f4f5"
  ink: "#18181b"
  ink-strong: "#09090b"
  ink-secondary: "#71717a"
  ink-muted: "#a1a1aa"
  border: "#e4e4e7"
  border-hover: "#d4d4d8"
  border-focus: "#d4d4d8"
  primary: "#2563eb"
  primary-active: "#1d4ed8"
  primary-subtle: "#eff6ff"
  primary-subtle-text: "#1d4ed8"
  button-primary-bg: "#3f3f46"
  button-primary-bg-hover: "#52525b"
  on-primary: "#ffffff"
  on-dark: "#ffffff"
  error: "#dc2626"
  error-subtle: "#fef2f2"
  success: "#16a34a"
  success-subtle: "#f0fdf4"
  warning: "#d97706"
  warning-subtle: "#fffbeb"

typography:
  display-lg:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 30px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: -0.5px
  display-md:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 24px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: -0.3px
  title-lg:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 18px
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: 0
  title-md:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: 0
  title-sm:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: 0
  body-md:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body-sm:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  caption:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0
  caption-uppercase:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 11px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0.5px
  code:
    fontFamily: "JetBrains Mono, ui-monospace, SFMono-Regular, monospace"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  button:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: 0
  nav-link:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0
  data-cell:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0
  kpi-value:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 28px
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: -0.5px

rounded:
  sm: 4px
  md: 6px
  lg: 8px
  xl: 12px
  pill: 9999px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 64px

components:
  button-brand:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 10px 20px
    height: 40px
  button-brand-active:
    backgroundColor: "{colors.primary-active}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.md}"
  button-primary:
    backgroundColor: "{colors.button-primary-bg}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 10px 20px
    height: 40px
  button-primary-active:
    backgroundColor: "{colors.button-primary-bg-hover}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.md}"
  button-secondary:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 10px 20px
    height: 40px
    border: "1px solid {colors.border}"
  button-secondary-active:
    backgroundColor: "{colors.surface-secondary}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
  button-ghost:
    backgroundColor: transparent
    textColor: "{colors.ink-secondary}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 8px 14px
  button-ghost-active:
    backgroundColor: "{colors.surface-secondary}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
  text-link:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.body-md}"
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 56px
    borderBottom: "1px solid {colors.border}"
  sidebar:
    backgroundColor: "{colors.surface-secondary}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    width: 240px
    borderRight: "1px solid {colors.border}"
  sidebar-item:
    backgroundColor: transparent
    textColor: "{colors.ink-secondary}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.md}"
    padding: 8px 12px
  sidebar-item-active:
    backgroundColor: "{colors.primary-subtle}"
    textColor: "{colors.primary-subtle-text}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.md}"
  card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xl}"
    padding: "{spacing.lg}"
    border: "1px solid {colors.border}"
  card-elevated:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xl}"
    padding: "{spacing.lg}"
    border: "1px solid {colors.border}"
  stat-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xl}"
    padding: "{spacing.lg}"
    border: "1px solid {colors.border}"
  text-input:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xl}"
    padding: 10px 14px
    height: 40px
    border: "1px solid {colors.border}"
  text-input-focus:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xl}"
    border: "1px solid {colors.border-focus}"
  text-input-error:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xl}"
    border: "1px solid {colors.error}"
  select:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xl}"
    padding: 10px 14px
    height: 40px
    border: "1px solid {colors.border}"
  tab:
    backgroundColor: transparent
    textColor: "{colors.ink-secondary}"
    typography: "{typography.title-sm}"
    padding: 8px 14px
    rounded: "{rounded.md}"
    borderBottom: "2px solid transparent"
  tab-active:
    backgroundColor: "{colors.primary-subtle}"
    textColor: "{colors.primary-subtle-text}"
    typography: "{typography.title-sm}"
    rounded: "{rounded.md}"
    borderBottom: "2px solid {colors.primary}"
  badge-default:
    backgroundColor: "{colors.surface-secondary}"
    textColor: "{colors.ink-secondary}"
    typography: "{typography.caption}"
    rounded: "{rounded.pill}"
    padding: 2px 10px
  badge-success:
    backgroundColor: "{colors.success-subtle}"
    textColor: "{colors.success}"
    typography: "{typography.caption}"
    rounded: "{rounded.pill}"
    padding: 2px 10px
  badge-warning:
    backgroundColor: "{colors.warning-subtle}"
    textColor: "{colors.warning}"
    typography: "{typography.caption}"
    rounded: "{rounded.pill}"
    padding: 2px 10px
  badge-error:
    backgroundColor: "{colors.error-subtle}"
    textColor: "{colors.error}"
    typography: "{typography.caption}"
    rounded: "{rounded.pill}"
    padding: 2px 10px
  badge-brand:
    backgroundColor: "{colors.primary-subtle}"
    textColor: "{colors.primary-subtle-text}"
    typography: "{typography.caption-uppercase}"
    rounded: "{rounded.pill}"
    padding: 2px 10px
  data-table:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.data-cell}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.xl}"
  data-table-header:
    backgroundColor: "{colors.surface-secondary}"
    textColor: "{colors.ink-secondary}"
    typography: "{typography.caption}"
    borderBottom: "1px solid {colors.border}"
    padding: 10px 14px
  data-table-cell:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.data-cell}"
    borderBottom: "1px solid {colors.border}"
    padding: 10px 14px
  data-table-row-hover:
    backgroundColor: "{colors.surface-secondary}"
  divider:
    borderTop: "1px solid {colors.border}"
  tooltip:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-dark}"
    typography: "{typography.caption}"
    rounded: "{rounded.md}"
    padding: 6px 10px
  dialog-overlay:
    backgroundColor: "rgba(0, 0, 0, 0.5)"
  dialog:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xl}"
    padding: "{spacing.lg}"
    border: "1px solid {colors.border}"
  dropdown-menu:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.lg}"
    border: "1px solid {colors.border}"
    padding: 4px
  dropdown-item:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: 8px 12px
  dropdown-item-active:
    backgroundColor: "{colors.surface-secondary}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
  filter-bar:
    backgroundColor: "{colors.surface-secondary}"
    textColor: "{colors.ink}"
    rounded: "{rounded.lg}"
    padding: "{spacing.sm}"
    border: "1px solid {colors.border}"
  toast-success:
    backgroundColor: "{colors.success-subtle}"
    textColor: "{colors.success}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: 12px 16px
    border: "1px solid {colors.success}"
  toast-error:
    backgroundColor: "{colors.error-subtle}"
    textColor: "{colors.error}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: 12px 16px
    border: "1px solid {colors.error}"
  toast-warning:
    backgroundColor: "{colors.warning-subtle}"
    textColor: "{colors.warning}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: 12px 16px
    border: "1px solid {colors.warning}"
  empty-state:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-muted}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xl}"
    padding: "{spacing.xxl}"
    border: "1px dashed {colors.border}"
  page-header:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    padding: "{spacing.lg}"
    borderBottom: "1px solid {colors.border}"
---

## Overview

DeepBI is a flat, wireframe-analytic interface built on the **zinc skeleton + blue anchor** design language. The visual identity is intentionally restrained — white canvas, zinc-gray structural elements, and blue-600 as the sole action accent. Every surface is flat: no box-shadows, no gradients, no blurred backdrops. Depth is communicated entirely through border dividers and surface-tone shifts (white → zinc-50 → zinc-100).

The system has three surface modes that form a clear visual hierarchy:
1. **White canvas** (`{colors.canvas}` — #ffffff) — default page floor, content cards, dialogs
2. **Zinc secondary** (`{colors.surface-secondary}` — #fafafa) — sidebar, table headers, filter bars, hover states
3. **Zinc hover** (`{colors.surface-secondary-hover}` — #f4f4f5) — row hover, dropdown item hover, stronger hover feedback

The zinc palette is the structural skeleton — borders, dividers, secondary text, hover states, and primary button backgrounds. The blue palette is the action anchor — brand CTAs, selected states, links, and active indicators. The blue is used sparingly; most of the interface reads in zinc.

**Key Characteristics:**
- Flat wireframe aesthetic — no shadows, no elevation, no blur. Depth comes from `{colors.border}` (1px zinc-200) dividers and surface-tone shifts.
- White canvas (`{colors.canvas}` — #ffffff) with zinc-900 text (`{colors.ink}` — #18181b). Clean, high-contrast, data-display optimized.
- Blue-600 anchor (`{colors.primary}` — #2563eb). Used only on brand CTAs, selected sidebar items, active tabs, and text links. Never used as a decorative fill.
- Zinc-700 primary buttons (`{colors.button-primary-bg}` — #3f3f46). The default action button is zinc, not blue — blue is reserved for the single highest-priority brand action.
- Inter geometric sans across all levels — headings, body, captions, buttons, navigation. No serif. Consistent, neutral, data-first.
- JetBrains Mono for code blocks, SQL snippets, and data identifiers.
- Hierarchical border radius: `{rounded.xl}` (12px) on outermost containers (cards, dialogs, inputs), `{rounded.md}` (6px) or `{rounded.lg}` (8px) on inner elements (buttons, tabs, dropdown items).
- Section rhythm `{spacing.section}` (64px). Internal card padding stays at `{spacing.lg}` (24px).
- Custom component className convention: every custom component's outermost element carries `ui-{kebab-name}` (e.g. `ui-data-table`, `ui-stat-card`). This class does not add or remove DOM nodes — it is a namespacing label only.

## Colors

### Brand & Accent
- **Blue / Primary** (`{colors.primary}` — #2563eb): The sole brand accent. Used on brand CTAs (`{component.button-brand}`), selected sidebar items, active tab underlines, text links, and badge accents. Never used as a decorative background fill — blue is a signal, not a decoration.
- **Blue Active** (`{colors.primary-active}` — #1d4ed8): The press / hover-darker variant for brand buttons.
- **Blue Subtle** (`{colors.primary-subtle}` — #eff6ff): Selected sidebar item background, selected tab background. Always paired with blue-700 text.
- **Blue Subtle Text** (`{colors.primary-subtle-text}` — #1d4ed8): Text on blue-subtle backgrounds. Also used for active nav link indicators.

### Surface
- **Canvas** (`{colors.canvas}` — #ffffff): The default page floor. Pure white — optimized for data density and chart readability.
- **Surface Secondary** (`{colors.surface-secondary}` — #fafafa / zinc-50): Sidebar background, table header rows, filter bars, hover states on secondary buttons. The default "one step down" surface.
- **Surface Secondary Hover** (`{colors.surface-secondary-hover}` — #f4f4f5 / zinc-100): Stronger hover feedback on dropdown items, table rows, and interactive list items.

### Text
- **Ink** (`{colors.ink}` — #18181b / zinc-900): All headlines, body text, and primary content. Near-black with a slight cool undertone from the zinc palette.
- **Ink Strong** (`{colors.ink-strong}` — #09090b / zinc-950): Reserved for KPI values and critical data points that demand maximum contrast.
- **Ink Secondary** (`{colors.ink-secondary}` — #71717a / zinc-500): Sub-headings, descriptions, placeholder text, table headers, sidebar nav labels.
- **Ink Muted** (`{colors.ink-muted}` — #a1a1aa / zinc-400): Empty-state text, disabled labels, fine print.
- **On Primary** (`{colors.on-primary}` — #ffffff): Text on blue brand buttons and zinc primary buttons.
- **On Dark** (`{colors.on-dark}` — #ffffff): Text on dark tooltip backgrounds.

### Semantic
- **Error** (`{colors.error}` — #dc2626 / red-600): Error text, destructive action icons, error input borders.
- **Error Subtle** (`{colors.error-subtle}` — #fef2f2 / red-50): Error toast backgrounds, error badge fills.
- **Success** (`{colors.success}` — #16a34a / green-600): Success text, success toast borders, positive delta indicators.
- **Success Subtle** (`{colors.success-subtle}` — #f0fdf4 / green-50): Success toast backgrounds, success badge fills.
- **Warning** (`{colors.warning}` — #d97706 / amber-600): Warning text, warning toast borders.
- **Warning Subtle** (`{colors.warning-subtle}` — #fffbeb / amber-50): Warning toast backgrounds, warning badge fills.

### Border
- **Border** (`{colors.border}` — #e4e4e7 / zinc-200): The universal 1px divider. Used on cards, inputs, table cells, sidebar edges, dropdowns, and between sections. The primary tool for creating visual separation without shadows.
- **Border Hover** / **Border Focus** (`{colors.border-focus}` — #d4d4d8 / zinc-300): Input focus state border. Subtly darkens rather than changing color — the interaction feedback is tonal, not chromatic.

### Button Surfaces
- **Button Primary Bg** (`{colors.button-primary-bg}` — #3f3f46 / zinc-700): Default action button background. Zinc, not blue — blue is reserved for the brand CTA.
- **Button Primary Bg Hover** (`{colors.button-primary-bg-hover}` — #52525b / zinc-600): Primary button hover state.

## Typography

### Font Family
The system runs **Inter** as the universal geometric sans across all levels — headings, body, captions, buttons, and navigation. **JetBrains Mono** handles code blocks, SQL snippets, and data identifiers. The fallback stack walks `Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif` for UI text and `JetBrains Mono, ui-monospace, SFMono-Regular, "Cascadia Code", monospace` for code.

Inter was chosen for its high x-height, clean geometry, and excellent readability at small sizes — critical for a data-dense BI interface. The system uses weight 400 for body and weight 600 for headings; Inter at 600 reads as clear hierarchy without feeling heavy.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.display-lg}` | 30px | 600 | 1.2 | -0.5px | Page titles, dashboard names — Inter |
| `{typography.display-md}` | 24px | 600 | 1.25 | -0.3px | Section heads, modal titles — Inter |
| `{typography.title-lg}` | 18px | 600 | 1.4 | 0 | Card titles, sidebar section labels — Inter |
| `{typography.title-md}` | 16px | 600 | 1.4 | 0 | Widget titles, form labels — Inter |
| `{typography.title-sm}` | 14px | 600 | 1.4 | 0 | Tab labels, filter labels — Inter |
| `{typography.body-md}` | 14px | 400 | 1.55 | 0 | Default running text, descriptions — Inter |
| `{typography.body-sm}` | 13px | 400 | 1.55 | 0 | Secondary descriptions, toast body — Inter |
| `{typography.caption}` | 12px | 400 | 1.4 | 0 | Badge labels, table header text, timestamps — Inter |
| `{typography.caption-uppercase}` | 11px | 500 | 1.4 | 0.5px | Category tags, status labels — Inter |
| `{typography.code}` | 13px | 400 | 1.6 | 0 | Code blocks, SQL snippets — JetBrains Mono |
| `{typography.button}` | 14px | 500 | 1.0 | 0 | Standard button labels — Inter |
| `{typography.nav-link}` | 14px | 400 | 1.4 | 0 | Sidebar items, nav links — Inter |
| `{typography.data-cell}` | 13px | 400 | 1.4 | 0 | Table data cells — Inter |
| `{typography.kpi-value}` | 28px | 700 | 1.15 | -0.5px | KPI stat values, big numbers — Inter |

### Principles
Headings use weight 600 (semi-bold), never 700 outside of KPI values. The hierarchy communicates through size, not weight escalation. Inter at 600 provides clear visual separation from body at 400 without the aggressive density of weight 700 headlines.

Body type stays at weight 400 for all paragraphs and descriptions. Button labels jump to weight 500 for clarity at small sizes. The monospace face (JetBrains Mono) is reserved for code, SQL, and technical identifiers — never for UI labels.

Inter's tabular figures feature is used in data tables and KPI displays to ensure numbers align cleanly across rows.

## Layout

### Spacing System
- **Base unit:** 4px.
- **Tokens:** `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 12px · `{spacing.md}` 16px · `{spacing.lg}` 24px · `{spacing.xl}` 32px · `{spacing.xxl}` 48px · `{spacing.section}` 64px.
- **Section padding:** `{spacing.section}` (64px) — tighter than marketing sites; appropriate for a data-dense dashboard.
- **Card internal padding:** `{spacing.lg}` (24px) for content cards, stat cards, and dialogs.
- **Table cell padding:** 10px × 14px — compact enough for data density, tall enough for touch targets.

### Grid & Container
- **Max content width:** Full-width by default. DeepBI is a dashboard application, not a marketing page — content fills the viewport.
- **Sidebar + content layout:** Fixed 240px sidebar on the left (`{component.sidebar}`), fluid content area to the right. The sidebar carries a `{colors.border}` right-edge divider.
- **Card grids:** 3-up or 4-up stat cards at desktop (KPI row), 2-up at tablet, 1-up at mobile.
- **Data tables:** Full-width within their container. Horizontal scroll on mobile rather than collapsing columns.
- **Filter bar:** Full-width above data tables, carrying search input + filter dropdowns in a horizontal row.

### Whitespace Philosophy
The white canvas + zinc border system creates a clean, high-density layout where every pixel serves data display. Section padding at 64px (vs. the marketing-standard 96px) reflects the dashboard context — less breathing room, more data above the fold. Internal card padding at 24px balances readability with information density.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow, no border | Page background |
| Hairline border | 1px `{colors.border}` | Cards, inputs, table cells, sidebar edge, dropdowns, dialogs |
| Surface shift | `{colors.surface-secondary}` background — no shadow | Sidebar, table headers, filter bars, hover states |
| Stronger surface shift | `{colors.surface-secondary-hover}` background — no shadow | Row hover, dropdown item hover |
| Overlay | `rgba(0,0,0,0.5)` backdrop | Dialog/modal backdrop only |

The elevation philosophy is **border-first, shadow-never**. Every visual separation is a 1px zinc-200 border. There are zero box-shadows in the system — no `shadow-sm`, no `shadow-md`, no `shadow-lg`. Depth is communicated entirely through:
1. **Borders** — the primary separation tool. Cards, inputs, table cells, dividers all use the same `{colors.border}` stroke.
2. **Surface tone** — zinc-50 backgrounds recede from the white canvas; zinc-100 signals active/hover.
3. **Overlay** — a single dark scrim (`rgba(0,0,0,0.5)`) appears behind dialogs and modals to isolate them from the page.

No colorful shadows. No glow effects on inputs. No shadow-based elevation ramp.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.sm}` | 4px | Checkbox corners, tiny badges |
| `{rounded.md}` | 6px | Buttons (all variants), tabs, dropdown items, tooltips |
| `{rounded.lg}` | 8px | Inner cards, filter bars, toasts, dropdown menus |
| `{rounded.xl}` | 12px | Outermost containers only — content cards, stat cards, dialogs, text inputs, selects, data tables, empty states |
| `{rounded.pill}` | 9999px | Badge pills, status dots |
| `{rounded.full}` | 9999px / 50% | Avatar images, icon buttons |

### Border Radius Rule
`rounded-md` and `rounded-lg` for inner elements; `rounded-xl` reserved for outermost containers. This creates a nested-radius hierarchy: a card (`{rounded.xl}`) contains buttons and tabs (`{rounded.md}`), which is visually logical — inner elements are tighter, outer containers are softer. Inputs are the exception: they use `{rounded.xl}` because they are the outermost interactive surface in a form row.

### Icons & Illustrations
DeepBI uses a consistent outlined icon set (24px, 1.5px stroke weight) in `{colors.ink-secondary}` for default state and `{colors.ink}` for active/hover. No filled icons except for the selected state in sidebar navigation. No illustrations — the interface is data-first, not decorative. Empty states use a dashed border container (`{component.empty-state}`) with a muted icon and text, never an illustration.

## Components

### Top Navigation

**`top-nav`** — White nav bar pinned to the top of every page. 56px tall, `{colors.canvas}` background, `{colors.border}` bottom border. Carries the DeepBI logo/wordmark at left, a global search input center, and a right-side cluster with notification bell, help icon, and user avatar. The bottom border is the only separator — no shadow.

### Sidebar

**`sidebar`** — Fixed 240px left sidebar. `{colors.surface-secondary}` (zinc-50) background, `{colors.border}` right-edge border. Carries navigation sections with `{typography.caption-uppercase}` section labels in `{colors.ink-muted}`, and nav items below.

**`sidebar-item`** — Individual navigation link. Transparent background, `{colors.ink-secondary}` text, `{typography.nav-link}`, padding 8px × 12px, `{rounded.md}`. Hover shifts to `{colors.surface-secondary-hover}` background.

**`sidebar-item-active`** — Active/current navigation link. `{colors.primary-subtle}` (blue-50) background, `{colors.primary-subtle-text}` (blue-700) text. This is the most prominent blue element in the persistent chrome — the only place blue appears outside of explicit CTAs.

### Buttons

**`button-brand`** — The highest-priority action on the page. `{colors.primary}` (blue-600) background, `{colors.on-primary}` (white) text, `{typography.button}`, padding 10px × 20px, height 40px, `{rounded.md}`. Used for "Create", "Save", "Deploy" — the single most important action in the current view. Active state darkens to `{colors.primary-active}` (blue-700). There should be at most one brand button visible at a time.

**`button-primary`** — Default action button. `{colors.button-primary-bg}` (zinc-700) background, white text. Same sizing as brand button but zinc, not blue. Used for secondary actions, form submissions, "Apply" in filter bars. Active state lightens to `{colors.button-primary-bg-hover}` (zinc-600).

**`button-secondary`** — Outlined button. Transparent background, `{colors.ink}` text, 1px `{colors.border}` border, same sizing as primary. Active/hover shifts background to `{colors.surface-secondary}` (zinc-50). Used for "Cancel", "Reset", and actions that shouldn't draw visual weight.

**`button-ghost`** — Minimal button for low-priority actions. Transparent background, `{colors.ink-secondary}` text. Padding 8px × 14px, `{rounded.md}`. Hover shifts to `{colors.surface-secondary}` background and `{colors.ink}` text. Used for icon-only actions, row-level actions, "More" menus.

**`text-link`** — Inline text links in `{colors.primary}` (blue-600). The only blue text outside of selected states. Used in descriptions, help text, and "Learn more" links.

### Cards & Containers

**`card`** — The standard content container. `{colors.canvas}` (white) background, `{colors.ink}` text, 1px `{colors.border}` border, `{rounded.xl}`, internal padding `{spacing.lg}` (24px). No shadow. The border is the only elevation cue.

**`card-elevated`** — Identical to `card` in the DeepBI system. The "elevated" variant exists as a token for future differentiation but currently shares all values with `card` — there is no shadow-based elevation.

**`stat-card`** — KPI display card. Same structure as `card` but optimized for a single big number + label. Carries `{typography.kpi-value}` (Inter 28px / 700) for the value, `{typography.caption}` in `{colors.ink-secondary}` for the label, and an optional delta indicator in `{colors.success}` (green) or `{colors.error}` (red).

### Inputs & Forms

**`text-input`** — Standard text input. `{colors.canvas}` (white) background, `{colors.ink}` text, `{typography.body-md}`, `{rounded.xl}`, padding 10px × 14px, height 40px, 1px `{colors.border}` border. No inner shadow, no ring.

**`text-input-focus`** — Focus state. Border shifts from `{colors.border}` (zinc-200) to `{colors.border-focus}` (zinc-300). The change is tonal (slightly darker zinc), not chromatic. No blue ring, no glow — consistent with the flat wireframe philosophy.

**`text-input-error`** — Error state. Border shifts to `{colors.error}` (red-600). Paired with an error message in `{typography.caption}` / `{colors.error}` below the input.

**`select`** — Dropdown select. Same styling as `text-input` — white background, zinc-200 border, `{rounded.xl}`. Carries a custom chevron icon.

### Tabs

**`tab`** — Inactive tab. Transparent background, `{colors.ink-secondary}` text, `{typography.title-sm}`, padding 8px × 14px, `{rounded.md}`, transparent bottom border (2px). Hover shifts text to `{colors.ink}`.

**`tab-active`** — Active tab. `{colors.primary-subtle}` (blue-50) background, `{colors.primary-subtle-text}` (blue-700) text, 2px `{colors.primary}` (blue-600) bottom border. The blue underline is the primary active indicator; the blue-50 background reinforces it.

### Badges / Tags

**`badge-default`** — Neutral badge. `{colors.surface-secondary}` (zinc-50) background, `{colors.ink-secondary}` text, `{typography.caption}`, `{rounded.pill}`, padding 2px × 10px.

**`badge-success`** — Success/active status badge. `{colors.success-subtle}` (green-50) background, `{colors.success}` (green-600) text.

**`badge-warning`** — Warning/pending status badge. `{colors.warning-subtle}` (amber-50) background, `{colors.warning}` (amber-600) text.

**`badge-error`** — Error/failed status badge. `{colors.error-subtle}` (red-50) background, `{colors.error}` (red-600) text.

**`badge-brand`** — Brand/accent badge. `{colors.primary-subtle}` (blue-50) background, `{colors.primary-subtle-text}` (blue-700) text, `{typography.caption-uppercase}`. Used for "NEW", "BETA", feature flags.

### Data Table

**`data-table`** — Full-width data table. `{colors.canvas}` background, 1px `{colors.border}` border, `{rounded.xl}`, overflow hidden. The table is the core DeepBI component — every design decision (zinc borders, compact spacing, monospace for identifiers) serves table readability.

**`data-table-header`** — Sticky header row. `{colors.surface-secondary}` (zinc-50) background, `{colors.ink-secondary}` text, `{typography.caption}`, `{colors.border}` bottom border, padding 10px × 14px.

**`data-table-cell`** — Standard data cell. `{colors.canvas}` background, `{colors.ink}` text, `{typography.data-cell}`, `{colors.border}` bottom border (row divider), padding 10px × 14px.

**`data-table-row-hover`** — Row hover state. Background shifts to `{colors.surface-secondary}` (zinc-50). No shadow, no border change — pure surface-tone feedback.

### Overlays & Feedback

**`dialog-overlay`** — Modal backdrop. `rgba(0, 0, 0, 0.5)` semi-transparent black. The only non-border depth mechanism in the system.

**`dialog`** — Modal dialog. `{colors.canvas}` background, 1px `{colors.border}` border, `{rounded.xl}`, padding `{spacing.lg}`. No shadow — the overlay provides all the depth isolation. Carries a `{typography.display-md}` title, body content, and a button row (typically `{component.button-secondary}` for "Cancel" + `{component.button-primary}` for "Confirm").

**`dropdown-menu`** — Popover menu. `{colors.canvas}` background, 1px `{colors.border}` border, `{rounded.lg}`, padding 4px. No shadow.

**`dropdown-item`** — Menu item. Transparent background, `{colors.ink}` text, `{typography.body-md}`, padding 8px × 12px, `{rounded.md}`.

**`dropdown-item-active`** — Hovered/active menu item. `{colors.surface-secondary}` background.

**`tooltip`** — Dark tooltip. `{colors.ink}` (zinc-900) background, `{colors.on-dark}` (white) text, `{typography.caption}`, `{rounded.md}`, padding 6px × 10px. No shadow — the dark background provides sufficient contrast against the white canvas.

**`toast-success`** — Success notification. `{colors.success-subtle}` background, `{colors.success}` text, 1px `{colors.success}` border, `{rounded.lg}`, padding 12px × 16px.

**`toast-error`** — Error notification. `{colors.error-subtle}` background, `{colors.error}` text, 1px `{colors.error}` border.

**`toast-warning`** — Warning notification. `{colors.warning-subtle}` background, `{colors.warning}` text, 1px `{colors.warning}` border.

### Filter Bar

**`filter-bar`** — Horizontal filter row above data tables. `{colors.surface-secondary}` (zinc-50) background, 1px `{colors.border}` border, `{rounded.lg}`, padding `{spacing.sm}` (12px). Carries a search `{component.text-input}`, filter `{component.select}` dropdowns, and an "Apply" `{component.button-primary}`.

### Page Structure

**`page-header`** — Top-of-content-area header bar. `{colors.canvas}` background, `{colors.border}` bottom border, padding `{spacing.lg}`. Carries the page title in `{typography.display-lg}`, breadcrumbs in `{typography.caption}` / `{colors.ink-muted}`, and a right-aligned action button (`{component.button-brand}` if there's a primary page action).

**`empty-state`** — Empty data placeholder. `{colors.canvas}` background, `{colors.ink-muted}` text, `{typography.body-md}`, `{rounded.xl}`, generous padding `{spacing.xxl}` (48px), 1px dashed `{colors.border}`. The dashed border (rather than solid) signals "nothing here yet" vs. a content card.

**`divider`** — Horizontal rule. 1px `{colors.border}` solid line. Used between sections within a card or page.

## Do's and Don'ts

### Do
- Anchor every page on the white canvas (`{colors.canvas}`). The white background maximizes data contrast and chart readability.
- Use `{colors.border}` (zinc-200) 1px borders for all visual separation. Borders are the system's only depth mechanism.
- Reserve `{colors.primary}` (blue-600) for the single highest-priority action per view. One brand button maximum.
- Use `{colors.button-primary-bg}` (zinc-700) for default actions. Zinc buttons are the workhorse; blue buttons are the signal.
- Apply `{rounded.xl}` (12px) only to outermost containers — cards, dialogs, inputs, tables. Inner elements use `{rounded.md}` (6px) or `{rounded.lg}` (8px).
- Use `{colors.surface-secondary}` (zinc-50) for hover states, selected rows, sidebar, and table headers. Surface tone is the only hover feedback mechanism.
- Prefix every custom component's outermost element with `ui-{kebab-name}` (e.g. `ui-stat-card`, `ui-data-table`, `ui-filter-bar`). This is a className label only; do not add or remove DOM nodes for it.
- Use JetBrains Mono for all code, SQL, and technical identifiers.
- Pair semantic badges with their subtle backgrounds: green-600 text on green-50 fill, red-600 on red-50, amber-600 on amber-50.

### Don't
- Don't add box-shadows. No `shadow-sm`, `shadow-md`, `shadow-lg`, or custom shadows. Flat wireframe means flat.
- Don't use colorful shadows or glow effects. No `shadow-blue-500/50`, no ring-color on focus — the focus state is a zinc border tone shift only.
- Don't use blue as a decorative fill. Blue-600 is an action anchor, not a section background or card color.
- Don't use multiple brand buttons per view. If everything is blue, nothing is.
- Don't use `{rounded.xl}` on inner elements. The radius hierarchy (xl → lg/md → sm) must be consistent.
- Don't add hover state styling beyond what the system encodes: surface tone shift (zinc-50 or zinc-100) or color darkening (blue-600 → blue-700, zinc-700 → zinc-600).
- Don't use gradients. Flat means flat.
- Don't add extra divider borders. One `{colors.border}` between elements is sufficient — no double borders, no alternating border colors.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 768px | Sidebar collapses to hamburger or bottom tab bar; stat cards 1-up; data tables horizontal-scroll; dialogs go fullscreen; filter bar wraps to vertical stack |
| Tablet | 768–1024px | Sidebar may collapse to icon-only (56px); stat cards 2-up; filter bar stays horizontal but may wrap |
| Desktop | 1024–1440px | Full 240px sidebar; 3-up or 4-up stat cards; full filter bar; data tables full-width |
| Wide | > 1440px | Same as desktop; content can optionally cap at a max-width or remain fluid |

### Touch Targets
- `{component.button-brand}` and `{component.button-primary}` at minimum 40 × 40px.
- `{component.text-input}` and `{component.select}` height at 40px.
- `{component.sidebar-item}` padding ensures effective tap area ≥ 44px.
- `{component.dropdown-item}` padding 8px × 12px yields effective tap area ≥ 44px at 14px font size.

### Collapsing Strategy
- Sidebar collapses to a 56px icon-only rail at tablet, and to a bottom tab bar or hamburger drawer at mobile.
- Stat card grids reduce columns rather than scaling cards down.
- Data tables retain all columns; horizontal scroll on mobile rather than hiding columns.
- Filter bars wrap inputs vertically on mobile rather than shrinking them.
- Dialogs go fullscreen (100vw × 100vh, no border-radius) at mobile widths.

## Iteration Guide

1. Focus on ONE component at a time. Reference its YAML key (`{component.stat-card}`, `{component.data-table}`).
2. Variants of an existing component (`-active`, `-error`, `-hover`) live as separate entries in `components:`.
3. Use `{token.refs}` everywhere — never inline hex values.
4. Never document hover as a separate visual state unless it changes more than one property. Default and Active/Pressed states are the canonical variants.
5. Inter at weight 400 / 600 is the universal typeface. No serif, no weight 300, no weight 800.
6. White + zinc + blue is the trinity. Don't introduce a fourth palette (no purple, no teal, no warm gray).
7. When in doubt about emphasis: bigger Inter size before bolder weight. The only weight 700 in the system is `{typography.kpi-value}`.
8. Every custom component outermost element gets `ui-{kebab-name}`. If the component is `DataTable`, the class is `ui-data-table`.

## Known Gaps

- Inter and JetBrains Mono are available as free Google Fonts / open-source fonts. No licensing gaps.
- The DeepBI logo and wordmark are not formalized as system tokens. Treat them as brand assets.
- Animation and transition timings (sidebar collapse, dropdown open/close, toast enter/exit, dialog mount) are not in scope. Default to 150ms ease-out for micro-interactions.
- Chart and visualization colors (for dashboard charts, line graphs, bar charts) are not defined here — this document covers the UI chrome, not the data visualization palette.
- Dark mode is not in scope for this version. The system is designed for light mode only.
- Form validation patterns beyond `{component.text-input-error}` (multi-field validation, server-error states, inline async validation) are not extracted.
- The specific chart library and its theme tokens (ECharts, Recharts, D3) are out of scope for this UI-chrome document.
- Loading states (skeleton screens, spinner placement, progressive table loading) are not yet formalized.
- Multi-level nested sidebar navigation (expandable sections, N-level tree) is not covered — the current spec assumes a flat or single-level nav structure.
