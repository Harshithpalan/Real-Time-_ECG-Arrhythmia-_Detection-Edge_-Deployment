---
name: Bio-Signal Edge Intelligence
colors:
  surface: '#0f131d'
  surface-dim: '#0f131d'
  surface-bright: '#353944'
  surface-container-lowest: '#0a0e18'
  surface-container-low: '#171b26'
  surface-container: '#1c1f2a'
  surface-container-high: '#262a35'
  surface-container-highest: '#313540'
  on-surface: '#dfe2f1'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#dfe2f1'
  inverse-on-surface: '#2c303b'
  outline: '#849495'
  outline-variant: '#3a494b'
  surface-tint: '#00dce6'
  primary: '#e0fdff'
  on-primary: '#00373a'
  primary-container: '#00f2fe'
  on-primary-container: '#006a70'
  inverse-primary: '#00696f'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#e1ffec'
  on-tertiary: '#003824'
  tertiary-container: '#67f4b7'
  on-tertiary-container: '#006e4b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ff6ff'
  primary-fixed-dim: '#00dce6'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f53'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0f131d'
  on-background: '#dfe2f1'
  surface-variant: '#313540'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 3rem
    fontWeight: '700'
    lineHeight: 3.5rem
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 2rem
    fontWeight: '600'
    lineHeight: 2.5rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
  body-sm:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1.125rem
  label-telemetry-lg:
    fontFamily: JetBrains Mono
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.5rem
    letterSpacing: -0.02em
  label-telemetry-md:
    fontFamily: JetBrains Mono
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
    letterSpacing: 0em
  label-telemetry-sm:
    fontFamily: JetBrains Mono
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: 1rem
    letterSpacing: 0.025em
  label-micro:
    fontFamily: JetBrains Mono
    fontSize: 0.625rem
    fontWeight: '600'
    lineHeight: 0.75rem
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system delivers the clinical authority, low-latency responsiveness, and surgical precision required by real-time biomedical AI diagnostic consoles and edge telemetry platforms. 

The aesthetic synthesizes high-density research instrumentation with contemporary glassmorphic luminescence:
- **Clinical Rigor & Zero Ambiguity:** Visual noise is stripped away. Density is calibrated for high-stress diagnostic scenarios where data integrity and split-second pattern recognition save lives.
- **Luminous Edge Instrumentation:** The interface draws inspiration from dark-room surgical displays, high-speed waveform oscilloscopes, and real-time edge inference telemetry. Pure chromatic light cuts through deep, non-reflective slate backgrounds.
- **Controlled Luminescence:** Accents employ precise visual containment—subtle photon glows along ECG trace vectors and hardware status indicators reinforce focus without causing optical fatigue or halo degradation during continuous monitoring shifts.

## Colors

The palette leverages a calibrated dark spectrum designed to maximize contrast ratios and preserve visual fidelity for continuous live biomedical telemetry.

### Palette Architecture
- **Base Substrates:** 
  - Canvas Deep: `#0B0F19` (lowest layer, infinite depth)
  - Surface Mid: `#111827` (card panels, metric containers)
  - Surface Elevated: `#1E293B` (overlays, modal dialogs, interactive hover targets)
- **Primary Telemetry (`#00F2FE` & `#06B6D4`):** Active signal vectors, live continuous ECG lead traces, primary AI inference confidence scores, and high-frequency edge execution metrics.
- **Physiological Normal (`#10B981`):** Strictly reserved for sinus rhythm confirmations, nominal blood gas metrics, operational edge sensor status, and completed model synchronization.
- **Telemetry Watch & Drift (`#F59E0B`):** Parameter drift, signal-to-noise ratio degradation, battery/thermal throttles on edge hardware, and non-sustained ectopic beats.
- **Ventricular & Critical Override (`#EF4444`):** Non-negotiable critical alert threshold. Reserved exclusively for ventricular tachycardia, ventricular fibrillation, asystole alerts, and terminal hardware read errors. Never used decoratively.
- **Interface Borders & Outlines:** Low-opacity cyan-tinted borders (`rgba(6, 182, 212, 0.16)`) and panel dividers (`rgba(255, 255, 255, 0.06)`).

## Typography

The typography architecture bridges human clinical diagnosis and machine-level telemetry processing through a strict dual-font hierarchy.

- **Primary Diagnostic Font (Inter):** Deployed across all clinical narratives, anatomical section headers, patient context, diagnostic classifications, and instructional workflows. High x-height ensures immediate readability under off-angle viewing conditions.
- **Machine & Metric Font (JetBrains Mono):** Mandated for all quantitative data streams: millivolt readouts, real-time heart rate (BPM), heart rate variability (HRV), edge inference latency (ms), floating-point model weights, sampling frequencies (Hz), and universal UTC timestamps.
- **Tabular Alignment:** All numerals are tabular figures (`font-variant-numeric: tabular-nums`) to prevent optical layout shift across high-frequency 250Hz–1000Hz live data renders.
- **Caps & Micro-Telemetry:** Category identifiers, channel descriptors (e.g., `LEAD V1`, `BANDWIDTH`, `DSP FILTER`), and alert statuses utilize `label-micro` with uppercase casing and expanded tracking for instant glanceability.

## Layout & Spacing

The layout operates on a high-density, mathematical 4px/8px incremental grid designed for modular clinical dashboards, edge device diagnostics, and multi-lead waveform canvases.

- **Grid Architecture:** 
  - Desktop (≥1280px): 12-column fluid grid with `gutter-desktop` (1.5rem) and `margin-desktop` (2rem). Supports multi-pane layouts: collapsible telemetry sidebar (3 cols), primary waveform trace workspace (6 cols), and real-time AI classification / inference stack (3 cols).
  - Tablet (768px - 1279px): 8-column layout with `gutter` (1rem) and `margin-tablet` (1.5rem). Inference metrics collapse beneath the primary trace monitor.
  - Mobile (<768px): 4-column layout with `gutter` (1rem) and `margin` (1rem). Waveform viewports lock to horizontal scroll locks, prioritizing single-lead feeds and primary status chips.
- **Data Spacing Principle:** Component gap rhythm prioritizes information proximity. Grouped physiological readings use `space-xs` and `space-sm` to maintain strong cognitive binding; macro dashboard modules separate via `space-lg` and `space-xl`.

## Elevation & Depth

Visual hierarchy is established using high-precision tonal layering, dark glassmorphism, and targeted trace luminescences rather than blunt drop shadows.

- **Surface Tiers:**
  - **Level 0 (Telemetry Floor):** `#0B0F19` with a subtle technical background reticle (10px grid composed of `rgba(255, 255, 255, 0.02)` lines).
  - **Level 1 (Sensor & Channel Containers):** Background `#111827` overlaid with a hairline border `1px solid rgba(6, 182, 212, 0.12)`.
  - **Level 2 (Active Focus Panels & Diagnostic Cards):** Background `rgba(30, 41, 59, 0.75)` supported by backdrop blur (`backdrop-filter: blur(12px)`) and a `1px solid rgba(0, 242, 254, 0.25)` edge.
  - **Level 3 (Modal Overrides & Emergency Triggers):** Solid `#1E293B` bordered with high-visibility alert states (`#EF4444` or `#00F2FE`).
- **Glow & Photon Architecture:**
  - Ambient glow is applied strictly to active state vectors: an ECG waveform stroke receives a `drop-shadow(0 0 6px rgba(0, 242, 254, 0.45))`.
  - Ventricular alert indicators generate a pulsing peripheral glow: `box-shadow: 0 0 16px rgba(239, 68, 68, 0.4)`.

## Shapes

The design system employs a soft, technical shape language (`roundedness: 1` = 0.25rem / 4px base radius) to reflect mechanical instrumentation and physical medical grade monitor enclosures.

- **Base Corner Radii:** Buttons, input inputs, tags, and small metric cells adhere strictly to `0.25rem` (4px).
- **Macro Containers:** Waveform canvas viewports, telemetry panels, and diagnostic modals use `rounded-lg` (`0.5rem` / 8px).
- **Tactile Geometric Discipline:** No pill buttons or fully spherical elements are permitted except for physiological status beacons (e.g., pulsing lead continuity indicators, 6px × 6px circles).
- **Edge Precision:** Corners remain crisp and defined to prevent decorative softening of serious medical telemetry interfaces.

## Components

### Buttons
- **Primary Inference Action:** Background `#00F2FE` with text `#0B0F19` (font: `Inter`, 600 weight). Hover state shifts to `#06B6D4` with a tight cyan field aura (`0 0 12px rgba(0, 242, 254, 0.35)`). Active state applies a `0.98` scale transform.
- **Secondary Telemetry Action:** Background `rgba(30, 41, 59, 0.6)`, text `#F8FAFC`, border `1px solid rgba(6, 182, 212, 0.25)`. Hover enhances border to `rgba(6, 182, 212, 0.5)` with text `#00F2FE`.
- **Critical Alert Trigger (Emergency Stop / Defib Flag):** Background `rgba(239, 68, 68, 0.15)`, text `#EF4444`, border `1px solid #EF4444`. On hover: solid `#EF4444` fill with `#0B0F19` text.

### Chips & Telemetry Status Badges
- **Structure:** Height 24px, padding `0 8px`, corner radius `0.25rem`. Typography is `label-micro` uppercase.
- **Sinus / Normal:** Background `rgba(16, 185, 129, 0.12)`, text `#10B981`, border `1px solid rgba(16, 185, 129, 0.3)`. Left icon is a static 4px emerald circle.
- **Ventricular Alert:** Background `rgba(239, 68, 68, 0.2)`, text `#EF4444`, border `1px solid #EF4444`. Left icon pulses via an infinite CSS beacon animation.
- **Edge Latency Chip:** Background `rgba(11, 15, 25, 0.8)`, text `#00F2FE`, border `1px solid rgba(0, 242, 254, 0.2)`. Numerical figures displayed via `JetBrains Mono`.

### Lists & Lead Channel Feeds
- **Channel Row:** Alternating subtle zebra styling (`#111827` to `rgba(17, 24, 39, 0.5)`), padding `space-sm space-md`, separated by `1px solid rgba(255, 255, 255, 0.04)`.
- **Row Columns:** Channel identity (`label-telemetry-sm`), live vector sparkline (width 120px), current absolute value (`JetBrains Mono`, right-aligned), and diagnostic confidence score (`body-sm`).

### Checkboxes & Radio Controls
- **Geometry:** 16px × 16px square, radius `2px`, border `1px solid rgba(6, 182, 212, 0.4)`, background `#0B0F19`.
- **Checked State:** Fill `#06B6D4`, check icon rendered in `#0B0F19`. Glow accent `0 0 6px rgba(6, 182, 212, 0.5)`.

### Input Fields & Parameter Steppers
- **Field Base:** Height 36px, background `#0B0F19`, border `1px solid rgba(255, 255, 255, 0.12)`, radius `0.25rem`, typography `label-telemetry-md` (`JetBrains Mono`), text `#F8FAFC`.
- **Focus State:** Border `1px solid #00F2FE`, box shadow `0 0 0 1px #00F2FE`.
- **Measurement Units:** Integrated trailing affix (e.g., `mV`, `ms`, `Hz`) rendered in `#64748B` (`Inter`, 500 weight).

### Cards & Diagnostic Panels
- **Container Structure:** Background `#111827`, border `1px solid rgba(6, 182, 212, 0.14)`, radius `0.5rem`.
- **Header Slot:** Height 40px, padding `0 space-md`, border-bottom `1px solid rgba(255, 255, 255, 0.06)`, display flex, align-items center, justify-content space-between. Header label in `label-telemetry-sm` (`#94A3B8`).

### Specialized Biomedical AI Components
- **Waveform Canvas Viewport:** Pitch black `#060911` display screen with embedded fine-ruled biomedical millivolt grid lines (`0.5px` solid `rgba(6, 182, 212, 0.08)` at 5mm/0.2s equivalence). Active signal path rendered in `#00F2FE` with `drop-shadow(0 0 4px #00F2FE)`.
- **Edge Model Telemetry Strip:** Horizontal pinned console bar reporting: Inference Latency (`JetBrains Mono` in `#10B981`), Quantization Scale (`FP16`), Memory Pressure (`MB / GB`), and Active Compute Engine (e.g., `NPU-0: ACTIVE`).