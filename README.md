# 🧩 FBC AMOLED Extender

> A flexible PCB extender to relocate an AMOLED display controller board in compact devices.  
> Designed specifically for the **Frog Boy Color** console to solve mechanical constraints.

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

---

## 📌 What is it?

This project provides a **38-pin, 0.35mm pitch FPC extender** board to help reposition the controller board of an AMOLED screen away from the display.  
It is especially useful when the display-controller stack is too thick and causes fitting issues inside enclosures (like in handheld consoles).

In the **Frog Boy Color**, it allows redistributing thickness away from the center, preventing the screen from being pushed outward.

---

## ⚙️ Features

- ✅ 38-pin FPC connector (JAE WP27D series compatible)  
- ✅ 0.35 mm pitch routing  
- ✅ Ultra-thin flexible PCB  
- ✅ Optimized for tight mechanical spaces  
- ✅ Designed for AMOLED screen integration  
- ✅ Fully open hardware (non-commercial)

---

## 🔧 Typical Usage

Host PCB ── AMOLED Controller ── FPC ── [📐 FBC Extender] ── FPC ── AMOLED Display


- Integrate between AMOLED Controller and AMOLED Display
- Reduces mechanical height at the center of the display
- Useful in modding, handhelds, embedded designs

---

## 📁 Files

| File                          | Description                            |
|-------------------------------|----------------------------------------|
| `FBC-AMOLED-Extender.kicad_pcb` | Main PCB layout                        |
| `FBC-AMOLED-Extender.sch`       | Schematic (if available)               |
| `gerber/`                       | Production-ready Gerber files          |
| `LICENSE.md`                   | Creative Commons license                |

---

## 📸 Gallery

*Coming soon – photos of the extender in a Frog Boy Color Color shell*

---

## 📜 License

This project is licensed under **CC BY-NC-SA 4.0**.

> ✔️ Use in personal projects  
> ✔️ Include in mod kits or finished products  
> ❌ Do not sell standalone at inflated prices  
> ❌ No commercial resale without permission

See [LICENSE.md](LICENSE.md) for full terms.

---

© 2025 Spiroy – Feel free to contribute, adapt, or improve!
