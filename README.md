# ✨ Card Beam Animation

<div align="center">

  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  ![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
  ![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

  <p align="center">
    <strong>A futuristic, high-performance sci-fi card streaming animation featuring real-time laser beam scanning, ASCII matrix morphing, and interactive Three.js particle dynamics.</strong>
  </p>

</div>

---

## 📖 Overview

**Card Beam Animation** is an interactive, cyberpunk-inspired visual experience built with vanilla web technologies and Three.js. As modular interface cards travel across an infinite horizontal conveyor stream, they intersect a central high-energy laser scanner beam. 

Upon crossing the threshold, cards dynamically disintegrate and morph into real-time ASCII code streams and glowing particle fields before reconstituting on the other side.

---

## 🌟 Key Features

- ⚡ **Laser Scanner Beam Effect**: A neon glowing central scanner with multi-phase clipping masks, glowing light dispersion, and dynamic particle emission.
- 🔠 **Real-Time ASCII Morphing**: Cards seamlessly transform into syntax-highlighted code streams as they intersect the beam scanner line.
- 🌌 **Dual-Canvas Particle System**: High-performance Three.js r128 and 2D HTML5 canvas particle engines simulating laser sparks, velocity dissipation, and reactive glowing dust.
- 🖱️ **Physics-Based Inertia Dragging**: Smooth mouse drag and touch gestures with momentum, inertia physics, and mouse wheel acceleration.
- 🎛️ **Interactive Controls**:
  - ⏸️ **Pause / Play**: Freeze animation at any exact intersection frame.
  - 🔄 **Reset**: Smoothly recalibrate the conveyor stream to original coordinates.
  - ↔️ **Direction**: Toggle bidirectional movement across the beam scanner.
  - ⏱️ **Real-Time Speed Indicator**: Dynamic velocity readout in `px/s`.
- 📱 **Fully Responsive**: Adapts fluidly across all viewport dimensions and display scales.
- 🪶 **Zero Build Overhead**: Written in pure HTML5, CSS3, and JavaScript — no bundler, compilation, or heavy frameworks required.

---

## 📂 Project Structure

```
Card_Beam_Animation/
├── index.html        # Main HTML structure, UI controls, and canvas mounts
├── index.css         # Modern dark-mode layout, neon glowing styles & typography
├── index.js          # Card stream physics, ASCII generation, and particle engine
├── .gitignore        # Ignored files and system artifacts
└── README.md         # Project documentation and guide
```

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/pabitralenka07/Card_Beam_Animation.git
cd Card_Beam_Animation
```

### 2. Run Locally

You can open `index.html` directly in any modern browser, or run a lightweight local HTTP server:

#### Using Python 3:
```bash
python3 -m http.server 8080
```
Then visit: `http://localhost:8080`

#### Using Node.js (`npx serve`):
```bash
npx serve .
```

#### Using VS Code:
Right-click `index.html` and select **"Open with Live Server"**.

---

## 🎮 Controls & Interactions

| Action | Control | Description |
| :--- | :--- | :--- |
| **Drag & Toss** | `Click + Drag` / `Touch + Swipe` | Manually flick or drag the cards with momentum |
| **Scroll Stream** | `Mouse Wheel` | Accelerate or reverse stream translation |
| **Toggle Play/Pause** | Button `⏸️ Pause` | Freeze and resume stream and particle loops |
| **Reset Position** | Button `🔄 Reset` | Recalibrate cards to starting coordinates |
| **Reverse Flow** | Button `↔️ Direction` | Flip horizontal direction (left ↔ right) |

---

## 🛠️ Built With

- **HTML5 Canvas** & **DOM Manipulation**: Seamless clipping mask coordination between DOM cards and canvas layers.
- **Vanilla CSS3**: Cyberpunk gradients, backdrop filters, flex layouts, and glowing laser effects.
- **JavaScript (ES6+)**: Custom momentum physics, stream velocity controllers, and dynamic procedural ASCII code generation.
- **[Three.js](https://threejs.org/) (r128)**: GPU-accelerated particle field rendering and glowing particle dynamics.

---

## ⚙️ Configuration & Customization

You can easily customize the beam scanner speed, particle counts, and styling inside `index.js`:

```javascript
// Change default streaming velocity
this.velocity = 120; // in px/s

// Modify scanner dimensions & glow in index.js
const SCAN_WIDTH = 8;
const MAX_PARTICLES = 2500;
```

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

<div align="center">
  Crafted with ❤️ by <a href="https://github.com/pabitralenka07">Pabitra Lenka</a>
</div>
