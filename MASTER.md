# Design System Master: HYPER LOOP MEDIA ® (Obsidian & Brushed Platinum Edition)

> **Brand Identity:** HYPER LOOP MEDIA ®
> **Core Pillars:** ✦ Video Editing & Creative Production · ✦ Turning Ideas Into Impact
> **Visual Direction:** Matched directly to the official **HYPER LOOP MEDIA ® (`HL`)** emblem — Deep Obsidian Velvet (`#030304`), Diagonal Volumetric Top-Right Studio Light Rays, Tactile Film Grain Noise, Brushed Platinum Silver Gradients, and Specular Edge Flares.

---

## 1. Color Tokens (Obsidian & Liquid Platinum Palette)

| Token | Dark Mode (Obsidian Studio — Default) | Light Mode (Platinum Daylight) | Role & Visual Character |
| :--- | :--- | :--- | :--- |
| `--bg-primary` | `#030304` (Obsidian Pitch Black) | `#F4F5F7` (Platinum Alabaster) | Deep studio backdrop matching logo corners |
| `--bg-elevated` | `#08090C` (Smoked Carbon) | `#FFFFFF` (Pure White) | Elevated sections, NLE deck chrome |
| `--surface-card` | `rgba(14, 15, 19, 0.78)` | `#FFFFFF` | Smoked glass cards with diagonal specular border |
| `--surface-highlight` | `#161820` (Anodized Graphite) | `#E5E7EB` | Hover surfaces & timeline tracks |
| `--border-subtle` | `rgba(255, 255, 255, 0.11)` | `#D1D5DB` | Crisp hairline architectural borders |
| `--border-specular` | `rgba(255, 255, 255, 0.38)` | `#6B7280` | Top-right lit edge matching logo light source |
| `--text-primary` | `#F8FAFC` (Pure Specular White) | `#090A0F` (Obsidian Ink) | $>18:1$ contrast |
| `--text-secondary` | `#C4C9D4` (Brushed Silver) | `#272B36` (Charcoal Slate) | $>10:1$ contrast |
| `--text-muted` | `#8E95A5` (Pewter Mist) | `#4B5262` (Muted Steel) | $\ge 5.2:1$ contrast (WCAG AA+) |
| `--accent-primary` | `#FFFFFF` (Pure White Flare) | `#111318` (Obsidian) | Primary metallic buttons & specular glints |
| `--accent-silver` | `#D8DCE6` (Liquid Platinum) | `#374151` (Graphite) | Gradient highlights & particle dust |
| `--status-green` | `#34D399` (Studio Lock Green) | `#059669` (Emerald) | Live booking & render lock status |

---

## 2. Best-in-Class Typography Stack (`ui-ux-pro-max` Curated)

- **Display / Hero Headlines (`--font-display`)**: `'Syne', sans-serif` (`700`, `800`) — Avant-garde, wide-stance agency display typeface that echoes the sharp geometric angles of the `HL` emblem.
- **Section Titles & Architectural UI (`--font-heading`)**: `'Space Grotesk', sans-serif` (`500`, `600`, `700`) — Precision kinetic geometric sans.
- **Body Copy (`--font-sans`)**: `'Manrope', sans-serif` (`400`, `500`, `600`, `700`) — Ultra-clean editorial legibility at all sizes.
- **Technical Metadata & Timecode (`--font-mono`)**: `'JetBrains Mono', monospace` (`400`, `500`, `600`) — Used for SMPTE timecodes, frame rates, and section indices.

---

## 3. Atmospheric Background, Particles & Choreographed Motion

1. **Diagonal Volumetric Light Shafts**: Fixed atmospheric light beam sweeping from the top-right (`-38deg`) across the `#030304` obsidian canvas, mirroring the exact lighting in `assets/hyperloop-logo.jpg`.
2. **Tactile Analog Grain Overlay**: Subtle SVG `feTurbulence` noise layer providing the brushed matte-platinum grain texture visible on the `HL` monogram.
3. **Interactive Studio Particle Engine (`#particleCanvas`)**:
   - Floating silver/platinum dust motes illuminated by the diagonal light beam.
   - Mouse-interactive parallax repulsion and faint constellation filaments.
   - Four-point specular star glints on key vertices.
4. **Scroll & Hover Choreography**:
   - Staggered reveal animations (`IntersectionObserver`) with `cubic-bezier(0.16, 1, 0.3, 1)` expo easing.
   - 3D perspective tilt & dynamic mouse-spotlight glow on Bento cards and the Hero Logo Monolith.
   - Animated impact number counters, infinite kinetic marquee, and full `prefers-reduced-motion` safety.
