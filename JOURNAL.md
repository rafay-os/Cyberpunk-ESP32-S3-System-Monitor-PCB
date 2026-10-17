# CYBERPUNK ESP32-S3 SYSTEM MONITOR - ENGINEERING JOURNAL

Welcome to the development log for the **Cyberpunk ESP32-S3 System Monitor PCB**. This journal tracks the detailed phase-by-phase design, routing, custom artwork integration, and DRC validation steps for Hack Club Fabricate.

---

## Log Entry 1: Schematic Capture & System Architecture
- **Date:** October 17, 2026
- **Phase:** Circuit Design & Component Selection
- **Status:** Completed

### Key Work Done:
- Designed the core schematic around the **ESP32-S3 microcontroller module**.
- Added USB-C interface for power delivery and data telemetry.
- Configured LDO power regulation (5V to 3.3V) with decoupling capacitors.
- Integrated OLED display pin headers and passive pull-up/pull-down components.

### Schematic Preview:
![Schematic Diagram](./schematic.png)

---

## Log Entry 2: PCB Placement & Signal Routing
- **Date:** October 17, 2026
- **Phase:** Board Layout & Routing
- **Status:** Completed

### Key Work Done:
- Placed power circuits, MCU module, and connector interfaces within board boundaries.
- Performed trace routing for power rails (`VCC`, `3V3`), Ground (`GND`), and high-frequency signal lines.
- Resolved trace crossovers and verified clearance rules using Design Rule Check (DRC).
- Achieved **0 DRC Errors** on final route check.

### 📷 2D PCB Layout View:
![2D PCB Layout](./2d_layout.png)

---

## Log Entry 3: Ground Plane Pour & Silkscreen Artwork
- **Date:** October 17, 2026
- **Phase:** Copper Fill & Branding
- **Status:** Completed

### Key Work Done:
- Applied a **Solid Ground Copper Pour (`GND`)** across the top layer to ensure low impedance, thermal relief, and EMI shielding.
- Adjusted copper region distance to board outline (`>= 10mil`) to resolve edge clearance warnings.
- Imported custom **ROEX Cyberpunk Logo** onto the `Top Silkscreen Layer` for custom visual identity.

### PCB Layout with Copper Pour & Silkscreen:
![PCB Layout with Copper Pour](./pcb_layout.png)

---

## Log Entry 4: 3D Visualization & Gerber Export
- **Date:** October 17, 2026
- **Phase:** Pre-Fabrication Quality Inspection
- **Status:** Ready for Manufacturing

### Key Work Done:
- Evaluated physical component clearances, USB-C port alignment, and silkscreen readability using EasyEDA 3D Viewer.
- Re-ran final DRC checks to guarantee manufacturing accuracy.
- Generated production-ready **Gerber zip files** for JLCPCB / Hack Club Fabricate submission.

### Final 3D Board Render:
![Cyberpunk ESP32-S3 3D Render](./3d_render.png)

---

## Summary Checklist

- [x] Schematic captured and verified[cite: 10]
- [x] PCB routed with 0 DRC errors[cite: 7, 12]
- [x] GND Copper pour applied[cite: 8, 11]
- [x] Custom silkscreen branding added[cite: 6]
- [x] 3D render verified[cite: 6, 13]
- [x] Gerber files exported
