---
name: Warm Nordic POS
colors:
  surface: '#fcf9f3'
  surface-dim: '#dcdad4'
  surface-bright: '#fcf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ed'
  surface-container: '#f0eee8'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e5e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#4f4540'
  inverse-surface: '#31312d'
  inverse-on-surface: '#f3f0ea'
  outline: '#81746f'
  outline-variant: '#d3c3bd'
  surface-tint: '#71594f'
  primary: '#0c0301'
  on-primary: '#ffffff'
  primary-container: '#2b1a12'
  on-primary-container: '#9b8075'
  inverse-primary: '#dfc0b3'
  secondary: '#994703'
  on-secondary: '#ffffff'
  secondary-container: '#fc934f'
  on-secondary-container: '#6d3000'
  tertiary: '#000502'
  on-tertiary: '#ffffff'
  tertiary-container: '#042311'
  on-tertiary-container: '#6c8d74'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fcdcce'
  primary-fixed-dim: '#dfc0b3'
  on-primary-fixed: '#281810'
  on-primary-fixed-variant: '#584238'
  secondary-fixed: '#ffdbc9'
  secondary-fixed-dim: '#ffb68c'
  on-secondary-fixed: '#321200'
  on-secondary-fixed-variant: '#753400'
  tertiary-fixed: '#c8ebce'
  tertiary-fixed-dim: '#accfb3'
  on-tertiary-fixed: '#02210f'
  on-tertiary-fixed-variant: '#2f4d38'
  background: '#fcf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e5e2dc'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  title-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  currency-display:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 0.75rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

This design system embodies a calm, Scandinavian-inspired hospitality aesthetic tailored for modern specialty cafes and roasteries. Combining high-efficiency mobile workflow ergonomics with warm minimalism, the interface eliminates cognitive clutter during peak service hours.

The emotional core is serene competence: baristas and floor staff experience a tool that feels more like an editorial lifestyle object than an industrial transaction engine. It achieves this balance by pairing tactile warmth—creamy oat undertones and dark roast espresso hues—with precise, utilitarian layouts. Surfaces employ structured, hairline tactile framing, soft diffuse drop shadows, and expansive touch ergonomics tailored for single-handed or thumb-zone mobile terminal operations.

## Colors

The palette draws directly from the sensory world of third-wave coffee craft and Nordic architectural interiors:

- **Primary (`#2B1A12` - Espresso Roast):** Used for critical primary actions, prominent headlines, active navigation nodes, and heavy structural emphasis.
- **Secondary (`#D97736` - Terracotta / Amber):** Delivers targeted focal points, primary badges, high-priority notifications, and the "Occupied" table status.
- **Tertiary (`#587860` - Soft Alpine Sage):** Conveys freshness and positive availability; strictly assigned to available tables, success validations, and completed line items.
- **Neutral (`#F9F6F0` - Oat Milk Canvas):** Forms the foundational background canvas, creating an inviting, low-glare surface that softens prolonged screen exposure.

### Semantic Floor & Table Management Statuses
- **Available:** `#587860` (Sage Green) paired with 12% tinted backdrops (`#EDF2EE`).
- **Occupied / Active Order:** `#D97736` (Warm Amber/Terracotta) with 12% tinted backdrops (`#FAF1EB`).
- **Reserved:** `#B85348` (Soft Nordic Rose) with 12% tinted backdrops (`#F8ECEB`).
- **Billed / Turnover Needed:** `#8E8881` (Muted Warm Slate) with 12% tinted backdrops (`#F3F1EF`).

### Surface & Border Hierarchy
- **Base Canvas:** `#F9F6F0`
- **Surface Elevation 1 (Cards, Sheets):** `#FFFFFF`
- **Surface Elevation 2 (Grouped Insets, Modals):** `#F3EFEA`
- **Tactile Border / Hairline:** `#E8E2D9` (creates precise micro-separation without visual noise).

## Typography

Typography relies entirely on Plus Jakarta Sans to combine modern Scandinavian geometry with organic humanist touches. 

- **Numerical Clarity:** All numeric figures, price outputs, and seat counts must enforce tabular figures (`font-variant-numeric: tabular-nums`) to prevent horizontal jitter during live tally updates.
- **Hierarchy in Fast Paced Environments:** High weight differentials (such as pairing `title-sm` with `label-sm` in dark espresso `#2B1A12` and slate `#736B63`) ensure order line items, modifier tags, and table timers can be processed at a brief glance from arms-length hand terminals.

## Layout & Spacing

The layout is optimized primarily for vertical mobile screens (375px–430px hand terminals) while fluidly adapting to compact landscape terminals and tablets.

- **Mobile Viewport Grid:** Operates on a fluid 4-column layout with `margin: 1rem` (16px) and `gutter: 0.75rem` (12px).
- **Table Management Floor Grid:** Renders in a 2-column or 3-column auto-fit matrix on mobile viewports. Each table tile maintains an aspect ratio close to 1:1, allowing staff to tap with zero layout drift.
- **Thumb Zone Design:** Critical action triggers (such as "Send to Barista," "Charge," or "Split Bill") are docked permanently into the bottom safe area (48px to 80px off the bottom bezel).
- **Navigation Drawer & Cart Panels:** The main navigation uses a left-anchored off-canvas drawer (width: 80vw, max-width 320px). The active order cart is rendered either as a persistent bottom docked peek-bar (showing item count and running total) that expands vertically into a full-height bottom sheet, or as an ergonomic side sheet on landscape devices.

## Elevation & Depth

Visual hierarchy uses warm, diffuse ambient drops instead of harsh synthetic shadows. This evokes the soft, natural light common in Scandinavian design.

- **Base Layer (Level 0):** Oat Canvas (`#F9F6F0`). Completely flat, anchoring overall application context.
- **Resting Cards & Tiles (Level 1):** Solid white surface (`#FFFFFF`) with a 1px tactile border in `#E8E2D9` and an ambient shadow: `box-shadow: 0 2px 8px -2px rgba(43, 26, 18, 0.04), 0 1px 3px 0 rgba(43, 26, 18, 0.02)`.
- **Active / Pressed Elements (Level 1 Interactive):** Scales subtly down to `0.98` with the border deepening to `#D3C7B9` to give instantaneous physical feedback without heavy color shifts.
- **Docked Bars & Bottom Sheets (Level 2):** `#FFFFFF` paired with an upward ambient spread: `box-shadow: 0 -4px 20px -2px rgba(43, 26, 18, 0.08)`.
- **Modals & Overlays (Level 3):** Backdrop blur tinted with warm deep espresso `rgba(43, 26, 18, 0.45)` with `backdrop-filter: blur(8px)`.

## Shapes

The design uses a balanced rounded radius (Level 2) that feels ergonomic and soft without veering into toy-like bubble aesthetics.

- **Default Radius (`0.5rem` / 8px):** Standard touch elements including input fields, category filters, and line item rows.
- **Large Radius (`1rem` / 16px):** Table visual modules, menu catalog item cards, and order slip containers.
- **Extra-Large Radius (`1.5rem` / 24px):** Slide-over sheets, floating pay bars, and modal dialogue cards.
- **Pill Radius (`9999px`):** Used strictly for dynamic status badges (e.g., "Available", "Occupied", "Bill Requested"), seat counters, and quick-add modifier counters.

## Components

### Buttons & Interactive Controls
- **Primary Buttons:** Background `#2B1A12` (Espresso), text `#FFFFFF`, height 52px (exceeding standard 44px minimum for zero-miss taps during rushes), rounded to 12px. Active press applies `scale(0.98)`.
- **Secondary Buttons:** Background `#FFFFFF`, 1px border in `#E8E2D9`, text `#2B1A12`.
- **Tertiary / Utility Action:** Soft amber tint background `#FAF1EB`, text `#D97736`, height 44px.

### Table Management Grid Cards
- Minimum touch bounding box: 104px × 104px.
- Enclosed within a 1px tactile border.
- Features prominent table number in `title-md`, seat count indicator in `label-sm`, and an active timer badge showing elapsed seated duration.
- State-specific accents:
  - *Available:* Sage accent dot (`#587860`), crisp white surface, border `#E8E2D9`.
  - *Occupied:* Amber accent border (`#D97736`), subtle background tint (`#FCF8F5`), high-contrast running balance.
  - *Reserved:* Rose indicator (`#B85348`), with guest name and arrival timestamp.
  - *Turnover / Cleaning:* Muted warm gray indicator (`#8E8881`), pulsing indicator dot.

### Chips & Filter Tabs
- Menu collection chips (e.g., "Pour Over", "Espresso", "Pastry", "Alternative Milks") are 36px in height with pill borders (`9999px`).
- Inactive state: `#FFFFFF` with `#E8E2D9` border and `#736B63` text.
- Selected state: `#2B1A12` fill with white text, casting a soft ambient shadow.

### Slide-Over Cart & Bottom Sheet Pay Drawer
- **Peek Bar:** Height 64px, docked to bottom, featuring total items count badge, total amount in `currency-display` (20px compact scale), and a right-aligned sliding "Review" chevron.
- **Expanded Cart Sheet:** Full-width slide-up view displaying discrete line items with clear modifier trees (e.g., "+ Oat Milk", "Extra Shot"). Each row features built-in swipe-to-delete or incremental numeric steppers (`-`, `+`) measuring at least 44px × 44px.

### Inputs & Modifiers
- Text & Numerical Keypad inputs feature `#FFFFFF` fill, 1.5px border `#E8E2D9`, and text `#2B1A12`.
- Focused state transitions border to `#D97736` without jarring drop shadows.
