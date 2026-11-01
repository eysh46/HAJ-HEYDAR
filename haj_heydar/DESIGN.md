---
name: HAJ_HEYDAR
colors:
  surface: '#10141a'
  surface-dim: '#10141a'
  surface-bright: '#353940'
  surface-container-lowest: '#0a0e14'
  surface-container-low: '#181c22'
  surface-container: '#1c2026'
  surface-container-high: '#262a31'
  surface-container-highest: '#31353c'
  on-surface: '#dfe2eb'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dfe2eb'
  inverse-on-surface: '#2d3137'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#adecff'
  on-secondary: '#003640'
  secondary-container: '#00d9fe'
  on-secondary-container: '#005b6b'
  tertiary: '#ffb2b7'
  on-tertiary: '#67001b'
  tertiary-container: '#ff7886'
  on-tertiary-container: '#780021'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#adecff'
  secondary-fixed-dim: '#00d9fe'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5d'
  tertiary-fixed: '#ffdadb'
  tertiary-fixed-dim: '#ffb2b7'
  on-tertiary-fixed: '#40000d'
  on-tertiary-fixed-variant: '#92002a'
  background: '#10141a'
  on-background: '#dfe2eb'
  surface-variant: '#31353c'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: '0'
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The brand personality embodies state-of-the-art cryptographic resilience, operational stealth, and technical precision. Designed for power users, developers, and privacy-focused individuals requiring impenetrable proxy tunnels and VPN protocols, the application delivers absolute control, security verification, and rapid connectivity.

The aesthetic fuses **Tactical High-Tech Cyberpunk** with **Refined Frosted Glassmorphism**:
- Ultra-deep obsidian layers overlaid with precision telemetry metrics.
- Laser-sharp borders, translucent micro-surfaces, and atmospheric cyan/emerald light sources reflecting cryptographically verified states.
- High-density information architecture balanced with clear visual hierarchy, accommodating bidirectional operational readiness (seamless LTR/RTL Persian and English interfaces).

## Colors
The color system operates strictly in a deep obsidian context, leveraging fluorescent spectral accents to project active telemetry, latency grades, and cryptographic states:

- **Primary (`#10b981` Emerald Glow):** Signifies an active, encrypted tunnel, operational integrity, optimal latency (<50ms), and positive verification.
- **Secondary (`#05daff` Electric Cyan):** Used for handshake operations, outbound routing, data packet visualization, and active interactive toggles.
- **Tertiary (`#f43f5e` Kinetic Crimson):** Dedicated to killswitch triggers, DNS leaks, critical packet drops, and node disconnection states.
- **Neutral Surface Palette:**
  - Base Obsidian Canvas: `#0d1117`
  - Elevated Container / Sidebar: `#161b22`
  - Card & Glass Surface: `rgba(22, 27, 34, 0.75)`
  - Tactical Border Grid: `rgba(255, 255, 255, 0.08)`
  - Elevated Border Highlight: `rgba(16, 185, 129, 0.3)` or `rgba(5, 218, 255, 0.3)`
  - Text High-Emphasis: `#f0f6fc`
  - Text Muted Telemetry: `#8b949e`

## Typography
Typography is organized into three deliberate roles:
1. **Space Grotesk** powers system headlines and operational status overviews with technical authority.
2. **Plus Jakarta Sans** provides clarity and warmth for descriptive text, user instructions, configuration labels, and standard UI elements.
3. **JetBrains Mono** delivers data metrics, ping times, IP addresses, port numbers, cryptographic hash previews, and protocol identifiers.

### RTL & Persian Font Integration
When rendering Persian/Arabic UI strings (e.g., حاج حیدر), the system maps to system-level Naskh/Kufi Grotesque counterparts (such as *Vazirmatn* or *Dana*) utilizing identical vertical metrics and optical weight hierarchy. Monospaced numeric indicators (latency in ms, speed in Mbps, and IP tables) retain `JetBrains Mono` with directional containment (`dir="ltr"` and `unicode-bidi: isolate`) to ensure absolute numeral alignment across RTL layouts.

## Layout & Spacing
The layout follows a responsive fluid grid with strict component hierarchy:
- **Desktop (>= 1200px):** 12-column layout. Sidebar navigation spans 3 columns, main connection telemetry and interactive world nodes span 6 columns, administrative telemetry and diagnostic drawer spans 3 columns. Section margin is `2rem` with a `1.25rem` gutter.
- **Tablet (768px - 1199px):** 8-column layout. Adaptive collapsible rail nav, centralized connection controller with sliding inspection panel.
- **Mobile (< 768px):** 4-column single-stack layout. The central interactive power ring occupies prime visual focus; ping diagnostics and node switchers collapse into swipeable glass cards. Gutters scale down to `0.75rem` with a `1rem` margin.

All directional margins and paddings automatically mirror under RTL rendering, switching start and end anchoring seamlessly.

## Elevation & Depth
Elevation is articulated through translucent dark glass layering, luminous multi-stop edge borders, and neon photonic blurs rather than muddy dropshadows:

1. **Canvas (Level 0):** Pure `#0d1117` with subtle hexagonal cybernetic grid texture at 3% opacity.
2. **Surface Containers (Level 1):** Solid `#161b22` with a `1px` border of `rgba(255, 255, 255, 0.06)`.
3. **Interactive Frosted Glass (Level 2):** `rgba(22, 27, 34, 0.65)` backdropped with `16px` blur (`backdrop-filter: blur(16px)`), combined with an inner highlight stroke (`inset 0 1px 0 rgba(255, 255, 255, 0.1)`).
4. **Active Signal Elevation (Level 3 - Connected State):** 
   - Radiates a dual diffuse atmospheric aura: `0 0 32px rgba(16, 185, 129, 0.25), 0 0 64px rgba(5, 218, 255, 0.15)`.
   - Sharp border illumination: `1px solid rgba(16, 185, 129, 0.6)`.
5. **Critical Alert Elevation:** Radiates `0 0 24px rgba(244, 63, 94, 0.3)` with `1px solid rgba(244, 63, 94, 0.8)`.

## Shapes
The design system relies on calibrated rounded geometry (`0.5rem` base, up to `1.5rem` for expansive cards) to offset the sharpness of technical monospaced statistics.

- Base buttons, inputs, and chips utilize standard `0.5rem` (8px) corner curvature.
- Structural cards and proxy node lists incorporate `1rem` (16px) curvature.
- Primary interaction nodes (the Main Connect Ring, status badges, protocol pills) use continuous pill or circular geometry (`50%` / `9999px`) to visually reinforce flow, speed, and cyclical encrypted connections.

## Components

### 1. Connection Core (Status Ring)
- **Central Action Unit:** A circular power orb (`180px` desktop, `140px` mobile).
- **Idle/Disconnected:** Dim slate ring (`rgba(255, 255, 255, 0.1)`), monochromatic center glyph, zero ambient aura.
- **Connecting:** Continuous double-orbit spinning stroke in Electric Cyan (`#05daff`) with trailing glow.
- **Connected:** Pulsing double neon ring in Emerald Green (`#10b981`), interior ambient particle glow, displaying real-time live throughput metrics in `JetBrains Mono`.

### 2. Buttons
- **Primary Cyber:** Solid emerald green fill (`#10b981`), charcoal black text (`#0d1117`), font weight 600, with hover box-shadow `0 0 16px rgba(16, 185, 129, 0.4)`.
- **Ghost/Tactical:** Translucent background (`rgba(255, 255, 255, 0.04)`), high-contrast border (`rgba(255, 255, 255, 0.12)`), text `#f0f6fc`. Hover state switches border to `#05daff` with `rgba(5, 218, 255, 0.1)` interior fill.
- **Danger (Killswitch):** Obsidian surface with crimson outline (`#f43f5e`), active state triggers high-intensity crimson flash.

### 3. Server Node List & Cards
- Glassmorphic panel with server ping indicators (signal meter bar colored according to MS thresholds: `<60ms` emerald, `60-140ms` cyan, `>140ms` amber).
- Includes national flag badge, cipher suite tag (e.g., `VLESS`, `TUIC`, `HYSTERIA-2`, `WIREGUARD`), and load percentage bar.
- On hover, transforms upward with a crisp cyan edge bleed.

### 4. Input Fields & Selectors
- Background: `#161b22`, border: `1px solid rgba(255, 255, 255, 0.1)`.
- Focus state: Border shifts to `#05daff`, subtle cyan field glow (`0 0 12px rgba(5, 218, 255, 0.2)`).
- Prefix and suffix telemetry adornments set in `JetBrains Mono` label-md.

### 5. Chips & Protocol Badges
- Compact capsules (`0.25rem` vertical, `0.75rem` horizontal padding).
- Frosted fill with a `1px` translucent border. Active encryption modes display an emerald dot with an animated pulse.

### 6. Admin & Creator Support Controls
- Dedicated high-access terminal card featuring VIP node deployment keys, dynamic upstream routing configurations, real-time traffic quotas, and single-click config backup tools.
- Creator support modules feature cryptographic donation address chips with integrated zero-knowledge QR code reveals and copy-hash feedback pulses.