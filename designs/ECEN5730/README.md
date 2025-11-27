# ECEN 5730 — PCB Design Coursework Portfolio

This directory contains four hardware design projects completed for **ECEN 5730: PCB Design** at the University of Colorado Boulder.  
Each board explores a distinct aspect of PCB engineering—ranging from beginner-level routing fundamentals to advanced multi-layer mixed-signal design.

All projects include schematics, PCB layouts, 3D renders, and structured documentation.

---

## 📘 Boards Included

### **1. 555 Timer Board**
A foundational PCB introducing:
- RC timing networks  
- Basic power routing  
- Clean single-sided signal flows  
- Switch control and LED loading  

**Folder:** [`board_1_555_timer`](board_1_555_timer)

---

### **2. Switching Noise Board — Good vs. Bad Layout**
A comparative board demonstrating how layout quality affects:
- Switching noise  
- Loop area & parasitic inductance  
- Decoupling placement  
- Return-path integrity  
- Digital signal ringing  

Includes identical logic circuits laid out two different ways.

**Folder:** [`board_2_switching_noise_with_good_and_bad_layout`](board_2_switching_noise_with_good_and_bad_layout)

---

### **3. Golden Arduino PCB**
A full microcontroller system designed from scratch:
- ATmega328P core + breakout headers  
- 16 MHz crystal  
- CH340 USB-UART interface  
- Reset circuitry  
- ESD protection  
- Power regulation and selection  
- I²C / UART / ICSP headers  
- Dense but controlled 2-layer routing  

**Folder:** [`board_3_golden_arduino_pcb`](board_3_golden_arduino_pcb)

---

### **4. Instrumentation Droid (4-Layer Mixed-Signal Board)**
An advanced multi-layer design integrating:
- ATmega328P microcontroller  
- DAC subsystem  
- Smart RGB LEDs (serial LEDs)  
- I²C sensor/OLED header  
- USB-UART interface  
- Buzzer driver  
- Extensive test points for measurement  
- Noise-aware 4-layer stack (Signal–GND–GND–Signal)  

This project emphasizes **mixed-signal layout, 4-layer stack planning, grounding strategy, and system-level integration**.

**Folder:** [`board_4_instrumentation_droid`](board_4_instrumentation_droid)

---

## 🎯 Skills Demonstrated

- Single-layer, 2-layer, and 4-layer PCB design  
- Mixed-signal routing (USB, DAC, LEDs, MCU)  
- Ground plane design & return-path control  
- Decoupling strategies for digital and analog subsystems  
- Clock routing fundamentals (8–16 MHz)  
- Power domain organization (USB, 5 V, 3.3 V)  
- Good vs. bad layout comparison and analysis  
- Schematic clarity & hierarchical organization  
- Documentation and PCB bring-up preparation  

---

## 🛠️ Tools Used

- **Altium Designer** (schematic + layout)  
- **Oscilloscope & lab instrumentation** (signal verification)  
- **Datasheet-driven component selection**  
- **Simulation tools as needed (LTspice, etc.)**  

---

## 📂 Folder Structure

```yaml
ECEN5730/
├── board_1_555_timer/
├── board_2_switching_noise_with_good_and_bad_layout/
├── board_3_golden_arduino_pcb/
├── board_4_instrumentation_droid/
└── README.md
```

---

## 🔒 Notes

This coursework is public and non-proprietary.  
Full design files are included for educational showcase and portfolio use.

