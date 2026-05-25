# IMPAX Digital Board

This design is a **multi-layer digital electronics board** developed for the **IMPAX payload electronics stack**. The board supports digital signal organization, payload interconnects, and system-level communication between the IMPAX detector electronics and the rest of the spacecraft/payload architecture.

The images below highlight the **PCB stack-up**, **3D board views**, **top-layer layout**, and a representative **schematic page** showing the digital board architecture.

All content is anonymized and intended purely as a PCB design portfolio example.

---

## 🔧 Board Overview

- Multi-layer PCB designed for payload digital electronics  
- Digital signal routing between payload subsystems  
- Board-to-board and cable connector interfaces  
- Organized connector pinout strategy for clean system integration  
- Local decoupling and power distribution for digital ICs  
- Careful grounding and return-path planning for signal integrity  
- Layout developed in **Altium Designer**  
- Designed as part of the **IMPAX CubeSat payload electronics effort**

This board functions as a **digital interface and routing board**, helping connect payload electronics in a structured and reviewable way while supporting clean digital communication across the system.

---

## 🛰️ Mission Context

**IMPAX** stands for **Imaging Microburst Precipitation with Atmospheric X-ray emissions**.

The mission is focused on studying relativistic electron microburst precipitation and associated atmospheric X-ray emissions. The payload electronics support measurement, control, and communication functions needed for the instrument system.

Within that electronics stack, the Digital Board contributes to the organization and routing of digital signals between payload subsystems.

---

## 🧱 Layer Stack Strategy

The PCB stack-up was selected to support:

- Clean digital routing  
- Low-impedance ground return paths  
- Separation between power distribution and signal routing  
- Improved signal integrity for board-level interfaces  
- Manufacturable routing density for a compact payload electronics board  

### Key stack features:

- Dedicated reference planes for digital signal return paths  
- Top and bottom layers used for component placement and local routing  
- Internal layers used for power, ground, and signal routing as needed  
- Via stitching and ground referencing used to improve layout robustness  
- Stack-up planning done with attention to payload electronics integration  

![Layer Stack](images/layer_stack.png)

---

## 🖼️ Image Gallery

### 1. 3D Views

**Top-side 3D**  
Shows the overall component placement, connector locations, and board-level mechanical organization.

![3D View – Top](images/layout_3d.png)

**Bottom-side 3D**  
Highlights the bottom-side component placement, routing support, and board-level layout symmetry.

![3D View – Bottom](images/layout_3d_bottom.png)

---

### 2. Top Layer Layout

Top copper view highlighting:

- Connector-driven layout organization  
- Digital signal routing between functional areas  
- Local decoupling near IC power pins  
- Ground-referenced routing strategy  
- Compact placement suitable for payload electronics packaging  

![Top Layer Layout](images/layout_top.png)

---

### 3. Digital Interface Architecture

The Digital Board supports the payload electronics system by organizing digital interfaces and interconnects between boards.

Key design considerations included:

- Keeping digital signal paths readable and traceable  
- Grouping related signals by connector and function  
- Maintaining clean reference paths for routed signals  
- Supporting future debugging through clear schematic and layout organization  
- Designing the board to fit within the larger IMPAX electronics stack  

This approach makes the board easier to review, debug, and integrate with the rest of the payload system.

---

### 4. Schematic Snapshot

Representative schematic page showing:

- Digital interface organization  
- Connector pin assignments  
- Power and ground connections  
- Signal grouping and naming strategy  
- Board-level electrical structure  

![Schematic Snapshot](images/schematic.png)

---

## 📁 Folder Contents

```text
IMPAX_Digital_Board/
├─ README.md
└─ images/
   ├─ layer_stack.png
   ├─ layout_3d.png
   ├─ layout_3d_bottom.png
   ├─ layout_top.png
   └─ schematic.png
```

---

## 🧠 Design Focus & Takeaways

This board demonstrates:

Multi-layer PCB planning for payload digital electronics
Connector-focused digital interface design
Clean schematic organization for collaborative review
Ground-referenced routing for digital signal integrity
Layout planning for compact CubeSat payload electronics
Altium-based documentation and portfolio presentation

This project reflects my approach to digital PCB design, where schematic clarity, connector organization, grounding strategy, and layout discipline are treated as important parts of the overall electronics architecture.

---

## ⚠️ Disclaimer

This repository contains a sanitized portfolio version of the IMPAX Digital Board documentation. Sensitive mission details, complete manufacturing files, full schematics, BOM data, and restricted design information are intentionally omitted.