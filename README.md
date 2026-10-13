# 🌌 Neon Horizon: Galaxy Devourer

![Neon Horizon Banner](https://img.shields.io/badge/Genre-Arcade%20%7C%20Space%20Shooter-00f3ff?style=for-the-badge)
![HTML5 / Canvas](https://img.shields.io/badge/Engine-HTML5%20Canvas-ff007f?style=for-the-badge)
![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind%20CSS-06b6d4?style=for-the-badge)
![Web Audio API](https://img.shields.io/badge/Audio-Web%20Audio%20API-f59e0b?style=for-the-badge)

**Neon Horizon: Galaxy Devourer** is a fast-paced, retro-futuristic top-down arcade space shooter built into a single self-contained HTML5 file. Battle through ten action-packed sectors filled with intense enemy waves, dynamic hazards, and unique boss encounters culminating in the ultimate showdown against **OMENA, The Galaxy Devourer**.

---

## ✨ Features

- **🎮 10 Escalating Levels & Bosses:** Unique boss mechanics for each sector, including orbital lasers, speed charges, invulnerable orbital shields, cloaking, freezing zones, and multi-phase bullet hells.
- **⚡ Dynamic Arsenal System:** Upgrade your firepower with 4 weapon modes:
  - **Plasma Cannon:** Balanced default weapon with high rate of fire.
  - **Spread Shot:** Wide-angle multi-directional burst.
  - **Laser Array:** Rapid-fire beam strikes.
  - **Homing Rockets:** Tracking missiles that lock onto enemy targets.
- **🛡️ Tactical Dash & EMP Bombs:** Evade danger usinginvulnerability dashes and unleash screen-clearing EMP Shockwaves to clear enemy projectiles.
- **🔊 Synthesized Web Audio Engine:** Built-in procedural sound effects generated dynamically via Web Audio API (no external sound file dependencies required).
- **🎨 Reactive UI & Neon Aesthetics:** Tailwind CSS HUD overlay, reactive particle engines, parallax starfields, and screen-shake visual effects.
- **📱 Responsive & Cross-Platform:** Full keyboard, mouse, and touch controls optimized for desktop and mobile play.

---

## 🕹️ Controls

| Action | Keyboard | Mouse / Touch |
| :--- | :--- | :--- |
| **Move Vessel** | `W`, `A`, `S`, `D` or `Arrow Keys` | Mouse Movement / Touch Drag |
| **Fire Main Weapon** | `Spacebar` | Left Click / Touch Hold |
| **Dodge Dash** | `Shift` (Left / Right) | — |
| **EMP Shockwave Bomb** | `E` | Right Click / UI Button |
| **Tactical Pause** | `P` | — |

---

## 🚀 How to Run

Because the game is designed as a self-contained web application, no installation or external web server is required.

1. **Clone or Download** this repository.
2. Open `neon_horizon_galaxy_devourer.html` directly in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Select your starting sector and click **ENGAGE HYPERDRIVE** to launch!

---

## 👾 Level & Boss Guide

1. **Sector 1 — Plasma Sentinel:** Introduces core mechanics with orbital laser rings.
2. **Sector 2 — Nebula Charger:** Fast-dashing boss dropping proximity explosive mines.
3. **Sector 3 — Shield Overlord:** Protected by a rotating, damage-reducing energy barrier.
4. **Sector 4 — Cluster Destroyer:** Heavy missile barrages that split on approach.
5. **Sector 5 — Void Weaver:** Generates a gravitational vortex pulling player vessels into danger.
6. **Sector 6 — Phantom Stalker:** Uses stealth cloaking technology and sudden high-speed strikes.
7. **Sector 7 — Inferno Dreadnought:** Fires giant thermal lasers sweeping across the screen.
8. **Sector 8 — Cryo Sentinel:** Chills the environment, slowing down player maneuverability.
9. **Sector 9 — Storm Harbinger:** Targets players with high-voltage lightning hazard zones.
10. **Sector 10 — OMENA (Galaxy Devourer):** A 3-phase final boss featuring bullet hells, black hole pulls, and enraged berserk sweeps.

---

## 🛠️ Tech Stack & Architecture

- **Markup & Layout:** Single-file HTML5 with dynamic HUD elements.
- **Rendering Engine:** Vanilla JavaScript utilizing HTML5 Canvas 2D Context (`requestAnimationFrame` loop).
- **Styling & Theme:** Tailwind CSS (via CDN) + Custom CSS Glassmorphism effects.
- **Audio Synthesizer:** Pure Web Audio API (`AudioContext`, `OscillatorNode`, `BiquadFilterNode`).

---

## 📄 License

This project is open-source and free to use, modify, and distribute for personal or educational purposes.
