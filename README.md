# 🚀 ORBITAL // Tic-Tac-Toe

A futuristic, cyberpunk-inspired 3D isometric Tic-Tac-Toe game built entirely with vanilla web technologies. Features responsive canvas particle physics, procedural background rockets with exhaust plumes, native Web Audio synthesis, and an unbeatable Minimax AI.

---

## 📸 Preview

> **Grid Sector 3×3 Active:** Claim the control deck before your opponent locks three aligned nodes across deep space.

---

## ✨ Features

- **Dynamic Cosmic Canvas:**
  - **Starfield:** Twinkling, multi-speed stars across depth layers.
  - **Rocket Fleet:** Procedurally generated spacecraft traversing the main menu background with custom vector drawing, glowing thruster trails, and fading exhaust sparks.
- **3D Isometric Grid:**
  - Board rendered with CSS 3D transforms and depth perspective (`translateZ`).
  - Interactive hover elevation and winning line pulse animations.
  - **Tilt View Toggle:** Instantly switch between an isometric 3D deck and a top-down flat perspective.
- **Multi-Tier AI Opponent:**
  - **Easy:** Casual play with occasional random moves.
  - **Medium:** Opportunistic blocking and tactical attacks.
  - **Hard:** Mathematically unbeatable opponent running the **Minimax** recursive decision algorithm.
- **Local Two-Player Mode:** Pass-and-play support for local 1v1 multiplayer.
- **Built-in Audio Synthesizer:**
  - Zero external `.mp3` or audio assets required.
  - Uses the **Web Audio API** to generate real-time oscillator frequencies for placing marks, hovering cells, winning chimes, and stalemate alerts.
  - One-click global mute/unmute control.
- **Score Persistence:** Real-time scoreboard with automatic `localStorage` caching to preserve stats across reloads.
- **Zero Dependencies:** Pure HTML5, CSS3, and modern Vanilla JavaScript.

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Markup & Structure** | HTML5 Semantic Elements, SVG Icons |
| **Styling & 3D** | CSS3 (Custom Properties, Perspective transforms, Keyframe animations) |
| **Background Systems** | HTML5 2D Canvas API (Starfield & Particle Rockets) |
| **Logic & AI** | Vanilla JavaScript (ES6+, Minimax Algorithm) |
| **Audio** | Web Audio API (OscillatorNode & GainNode synthesis) |

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/orbital-tic-tac-toe.git](https://github.com/baidiksengupta-bit/tic-tac-toe.git)
cd orbital-tic-tac-toe
