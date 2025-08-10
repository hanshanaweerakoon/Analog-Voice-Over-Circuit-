# Analog Voice-Over Circuit

This project implements an *analog voice-over circuit* that automatically switches between two audio channels:
1. Audio from a 3.5 mm input jack
2. Audio from a microphone (priority input)

When the microphone is active, the circuit mutes the 3.5 mm input and plays the mic audio through a speaker.  
The circuit is designed for *low noise and clear output* using optimized op-amp and filter configurations.

---

## Functional Block Diagram

<img width="464" height="416" alt="functional_block_diagram" src="https://github.com/user-attachments/assets/f772f094-2894-4e31-8e8a-fa24c00fccf5" />

---

## Features
- *Automatic audio switching* (mic priority)
- *Microphone biasing and pre-amplifier* with low-pass filter
- *Op-amp based precision rectifier* for control signal
- *Adjustable audio pre-amplifier* (volume control)
- *Push-pull power amplifier* using TIP41/TIP42
- *±12 V power supply* with voltage regulators
- *Custom PCB design* (dual-layer & single-layer)
- *3D printed enclosure* in black PLA

---

## Folder Structure
- /docs — Project report & presentation  
- /simulation — LTSpice circuit and simulation results  
- /pcb — PCB design files and Gerber files  
- /enclosure — SolidWorks design files & STL exports  
- /images — Rendered images and photos

---

## Hardware Overview
| Section | Components | Purpose |
|---------|------------|---------|
| Mic Pre-amp | TL072 op-amp, RC filter | Amplify mic signal, reduce noise |
| Switching | CD4066, comparators | Automatic channel selection |
| Power Amp | TIP41/TIP42 transistors | Drive speaker |
| Power Supply | 7812, 7912, transformer | Provide ±12 V rails |

---

## PCB Design

<img width="680" height="632" alt="pcb_3D_view" src="https://github.com/user-attachments/assets/7b9815b7-268b-44d4-ac7d-eb09392d7e46" />

---

## Enclosure Design

<img width="280" height="284" alt="Screenshot 2025-08-10 121109" src="https://github.com/user-attachments/assets/e1cca1f1-340d-4893-9a0a-23e8337f4053" />
<img width="280" height="284" alt="Screenshot 2025-08-10 121109" src="https://github.com/user-attachments/assets/2259db0e-51ea-47f0-a634-0fcc88b50369" />

---

## Authors
- *Jayasekara S.P.R* – PCB Design, Documentation
- *Peiris P.I.U* – Enclosure Design, Resource Management
- *Viduranga J.K.A* – Circuit Design, Debugging
- *Weerakoon W.M.B.H* – Circuit Design, Simulation, Testing


