# Pankaj Kumar – Creative Studio Portfolio
### Graphic Designer · UI/UX Architect · Creative Technologist

An interactive, responsive portfolio website featuring 3D gate/door opening physics, interactive design labs, Figma-style UI inspection, design systems tokens, and tactile Web Audio feedback.

---

## 🚀 Live Preview & Quick Start

### Option 1: Direct Browser Open (Zero Setup)
Simply double-click `index.html` or open it with your favorite browser:
- On Windows: Right-click `index.html` → **Open with** → **Google Chrome** (or Edge/Firefox).

### Option 2: Local HTTP Server (Recommended)
Using Node.js or Python in PowerShell/Terminal:

```powershell
# Using npm
npm start

# Or using Python
python -m http.server 3000
```
Then navigate to `http://localhost:3000`.

---

## 🌟 Upgraded UI/UX & Graphic Designer Features

### 🚪 1. Enhanced UI Gate Opening System
- **Cinematic 3D Entrance Gate**: Ornate dual gate wings with bevel moldings, brass knocker, glowing keyhole, and opening sound effects.
- **Instant Gate Re-opener**: A `🚪 Gate` button in the navigation to replay the entrance gate at any time.
- **3D Portal Doors with Interactive Rooms**: 4 architectural swinging gates for:
  - **UI/UX & Product Design**: Live interactive design system atomic tokens.
  - **Graphic Design & Branding**: Vector bezier geometry preview & mathematical balance.
  - **Web & Creative Development**: Responsive device simulator (desktop, tablet, mobile).
  - **App Design & Mobile UX**: Interactive smartphone simulator with notch and notification simulation.

### 🎨 2. The Creative Labs (Graphic Design Suite)
- **Color Palette Explorer**: 4 curated designer color harmonies (*Neon Studio*, *Swiss Clean*, *Tokyo Dusk*, *Editorial Forest*) with click-to-copy HEX codes and WCAG contrast ratings.
- **Typography & Scale Studio**: Live editable specimen text with interactive size range slider and Modern Sans / Editorial Serif typeface pairing toggle.
- **Logo Geometry & Golden Ratio Inspector**: Visual SVG anatomy with toggleable golden ratio ($\phi = 1.618$) construction circles, optical grid redlines, and 90° rotation test.
- **Design System Tokens Sandbox**: Interactive button states (Default, Active, Loading, Success), custom toggle switch, and progress metrics.

### 📐 3. Figma-Style "UI Inspect Mode" (`Press I`)
- **8px Designer Grid**: Projects an 8px grid overlay across the whole viewport.
- **Figma Redline Bounding Box**: Hovering over any element renders an outline with exact pixel dimensions (`W × H · <tag>`).
- **Live Cursor Coordinates**: Floating pill tracking `X` and `Y` screen coordinates.

### 🔊 4. Synthesized Audio Engine (Web Audio API)
- 100% offline, zero-asset synthesized wooden gate swooshes, tactile UI clicks, and harmonic toast chimes.
- Toggle sound on/off using the `🔊 Sound` button or pressing `[M]`.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| **`[I]`** | Toggle Figma-Style UI Inspect Mode |
| **`[T]`** | Toggle Dark / Light Theme |
| **`[M]`** | Toggle Sound Effects (Mute / Unmute) |
| **`[1] - [4]`** | Instantly open Gate 1, 2, 3, or 4 |
| **`[Esc]`** | Close open modals or exit Inspect Mode |

---

## 🛠️ Customization Guide

1. **Services & Behind-the-Door Sandboxes**:
   - Edit the `doorServices` array inside `<script>` in `index.html`.
2. **Color Palettes**:
   - Add or tweak palettes in the `curatedPalettes` array.
3. **Selected Work**:
   - Update project names, categories, and case study descriptions in array `W` and `INFO`.
4. **Pricing & Packages**:
   - Adjust rates and deliverables in `<section id="pricing">`.
