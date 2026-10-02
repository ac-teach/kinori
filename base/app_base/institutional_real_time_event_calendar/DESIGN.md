---
name: Institutional Real-Time Event Calendar
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
  on-surface-variant: '#3c4a42'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#6c7a71'
  outline-variant: '#bbcabf'
  surface-tint: '#006c49'
  primary: '#006c49'
  on-primary: '#ffffff'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#4edea3'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#855300'
  on-tertiary: '#ffffff'
  tertiary-container: '#e29100'
  on-tertiary-container: '#523200'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-compact: 0.5rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system establishes a high-performance, academic, and administrative calendar ecosystem engineered for clarity, institutional trust, and high operational velocity. Tailored for university administrations, faculty, researchers, and campus communities, the interface prioritizes immediate legibility, effortless temporal navigation, and real-time status orchestration across multi-track institutional schedules.

Drawing directly from contemporary productivity tooling, the visual language sits firmly at the intersection of **Corporate / Modern** precision and fluid product design:
- **Atmosphere:** Clean, daylight-drenched slate canvases framing saturated functional badges that guide the eye instantly to concurrent lectures, symposiums, athletic fixtures, and deadlines.
- **Rhythm:** Highly structured, rigorous grid layouts counterbalanced by softened surface containers, tactile interactive triggers, and low-cognitive-load time blocks.
- **Tone:** Authoritative yet approachable, eliminating bureaucratic clunkiness in favor of swift interaction, crisp outlines, and unambiguous categorical distinctions.

## Colors

The palette employs crisp Slate grays as its structural backbone, layered with high-clarity semantic accents dedicated to schedule categories and status tracking:

- **Canvas & Backgrounds:** Crisp default background set at `#f8fafc` (Slate 50) paired with elevated surface panels in pure `#ffffff`, bordered by hairline `#e2e8f0` (Slate 200) dividers. Dark contrasting text sits firmly at `#0f172a` (Slate 900) for uncompromised typographic contrast.
- **Brand & Primary Actions:** Emerald Green (`#10b981` / hover `#059669`) signals active states, live indicators, primary event creation, and confirmed status.
- **Institutional Blue / Secondary:** Indigo-Navy (`#2563eb` / hover `#1d4ed8`) grounds institutional identities, primary navigation filters, and focused controls.
- **Event Taxonomy Badges (Pills & Blocks):**
  - *Academic / Research:* Emerald tint (`bg: #ecfdf5`, `border: #a7f3d0`, `text: #065f46`).
  - *Institutional / General:* Slate Sky tint (`bg: #eff6ff`, `border: #bfdbfe`, `text: #1e40af`).
  - *Cultural / Arts:* Amber Orange tint (`bg: #fffbeb`, `border: #fde68a`, `text: #92400e`).
  - *Sports / Student Life:* Rose Red tint (`bg: #fff1f2`, `border: #fecdd3`, `text: #9f1239`).
  - *Live Indicator Line:* Pulsing Carmine Red (`#ef4444`) with subtle horizontal tracking rule for the current time axis.

## Typography

Typography relies entirely on **Inter** to ensure maximum metric regularity, high legibility across dense timetable matrices, and tabular numerical precision.

- **Tabular Figures (`tnum`):** All numerical representations—timestamps, date numbers, hour axes, and room capacities—must enforce tabular figures to prevent horizontal jitter during real-time status updates.
- **Hierarchy:** 
  - Section headers and month navigators leverage `headline-md` and `headline-lg` in semi-bold (`600`) to anchor views.
  - Calendar event titles utilize `label-md` or `label-sm` in medium and semi-bold weights for rapid scanning.
  - Auxiliary schedule metadata (duration, speaker names, virtual links) utilize `body-sm` rendered in muted slate (`#64748b`).
- **Caps & Badges:** Categorical tags and micro-labels adopt uppercase tracking with a letter spacing of `+0.04em` at `label-sm` to guarantee instant recognizability.

## Layout & Spacing

The structural layout uses a responsive multi-pane application architecture composed of a fixed secondary rail (category toggles and secondary mini-calendar), an expansive flexible timetable grid, and situational floating sidebars for event creation and real-time inspector panels:

- **Desktop Framework:** 
  - Left navigation rail: Fixed at 260px (collapsible to 72px icon dock).
  - Main timetable viewport: Fluid multi-column view (Day: 1 column, Week: 7 columns, Workweek: 5 columns) separated by precise 1px `#e2e8f0` grid rules.
  - Inspector Drawer / Popover: 380px contextual panel floating on the right plane or overlaid as an anchored modal card.
- **Grid Timetable Intervals:** Horizontal time markers (hourly) maintain a consistent baseline height of 64px, enabling clean fractional mapping for 15, 30, and 45-minute blocks.
- **Breakpoints:**
  - *Desktop (≥1280px):* Full calendar matrix with expanded dual sidebars and persistent view switcher.
  - *Tablet (768px – 1279px):* Collapsed icon rail, 3-to-5 day visible span, drawer-based filters.
  - *Mobile (<768px):* Single-day schedule view or continuous vertical agenda feed; bottom navigation sheet for quick actions.

## Elevation & Depth

Visual hierarchy combines clean surface planes with restrained ambient shadows and hairline borders:

- **Base Layer (Canvas):** Tone `#f8fafc` without shadow.
- **Structural Modules (Panels, Nav Rails, Calendar Containers):** Crisp pure white `#ffffff` cards bounded by `1px solid #e2e8f0` with a gentle floor shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.04)`.
- **Event Pills & Calendar Blocks:** Subdued flat tint surface (`bg-opacity: 85%`) accompanied by a subtle 1px border matched to the category palette. On hover or active focus, the block elevates with `0 4px 6px -1px rgba(15, 23, 42, 0.08)` and full opacity.
- **Contextual Overlays (Quick Add Modals, Flyouts):** Framed in high-tier elevation: `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.06)`, bounded by `#cbd5e1` to detach distinctly from grid lines beneath.
- **Live Now Bar:** Bright red indicator pin (`#ef4444`) with a pulsing ambient radial glow (`0 0 0 4px rgba(239, 68, 68, 0.2)`).

## Shapes

The design system maintains a modern, friendly, and structured aesthetic using roundedness level 2:

- **Containers & Major Panels:** Main application containers, modal forms, and calendar wrapper frames utilize `rounded-xl` (1rem / 16px).
- **Controls & Form Elements:** Input fields, dropdown triggers, and buttons use `rounded-lg` (0.5rem / 8px).
- **Event Blocks & Mini Badges:** Micro-events within grid cells feature `rounded-md` (0.375rem / 6px) to maximize internal text area while softening visual edges.
- **Status Indicators & Circular Triggers:** Date circle highlights (e.g., current day chip) and icon action circles implement full pill / circular geometry (`rounded-full`).

## Components

### Buttons & Interactive Controls
- **Primary Action (e.g., "+ Create Event"):** Solid Emerald (`#10b981`), white medium text, `px-4 py-2`, `rounded-lg`. Soft shadow on resting, translates down slightly on active press.
- **Segmented View Switcher (Day / Week / Month):** Encapsulated container in `#f1f5f9` with subtle border. Selected pill snaps with `#10b981` background or solid white card with elevated micro-shadow and bold slate label.
- **Icon Actions (Nav arrows, search, settings):** Borderless or ghost-bordered `#e2e8f0` squares (`size: 36px`, `rounded-lg`), hovering into `#f8fafc`.

### Event Blocks & Badges
- **Timetable Event Block:** Left-bordered indicator strip (3px solid category color) with a translucent tinted body. Contains:
  - Top row: Event title (`label-md`, bold Slate 900).
  - Bottom row: Time range (`label-sm`, muted tone).
- **Live Status Chip:** Micro-pill with pulsating green dot (`#10b981`) and uppercase text "EN VIVO" or "TRANSMITIENDO".

### Input Fields & Search
- **Search & Filters:** Integrated search bar with left-aligned `#64748b` icon, background `#ffffff`, border `#e2e8f0`, focused ring in `#2563eb` with 2px offset.
- **Event Creation Inputs:** Stacked minimal fields inside popovers; borderless title input using `headline-sm` placeholder followed by clean segmented selectors for location, date, category tag, and attendees.

### Cards & Drawers
- **Event Detail Inspector Card:** Clean white card featuring category badge banner, title, time, calendar export options (Google Calendar, Outlook, iCal), and real-time room capacity meter.
- **Mini Month Navigator:** Left sidebar calendar widget with compact day numbers, active day highlighted in `#10b981`, and event dots representing density.