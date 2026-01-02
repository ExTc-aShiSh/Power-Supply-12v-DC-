# 🔌 230V AC to 12V DC Rectifier PCB (KiCad)

This repository contains my **first-ever PCB design**, created using **KiCad** 🎉  
The project is a **230V AC to 12V DC rectifier circuit** with a built-in filtering stage, designed to convert mains AC into a smooth DC output suitable for low-voltage electronics.

> ⚠️ **Warning:** This project involves **230V AC mains voltage**. Handle with extreme care. Do not build or test this circuit unless you are familiar with proper high-voltage safety practices.

---

## 🔧 Circuit Overview

The circuit performs the following functions:
1. Steps down mains voltage  
2. Converts AC to DC  
3. Filters the DC output for smoother operation

### 🔹 Circuit Highlights
- **Step-down Transformer**  
  Converts **230V AC → 12V AC**

- **4× 1N4001 Diodes**  
  Configured as a **full-bridge rectifier**

- **2× Capacitors**  
  Used for **smoothing / filtering** the rectified DC

- **1× Resistor**  
  Limits current for the indicator LED

- **1× LED**  
  Indicates DC output status 💡

---

## 📁 Repository Contents

- KiCad **schematic** files  
- KiCad **PCB layout** files  
- Supporting project files for PCB fabrication

---

## 🖥️ View the Schematic & PCB Online

You can view the **schematic** and **PCB design** directly in your browser without installing KiCad:

👉 https://kicanvas.org

Upload or link this repository to KiCanvas to explore the design interactively.

---

## 🎯 Project Goals

- Learn PCB design basics  
- Understand AC–DC rectification  
- Gain hands-on experience with KiCad  
- Build confidence in hardware design

---

## 🚀 Possible Future Improvements

- Add voltage regulation (linear or SMPS)
- Include fuse, MOV, and protection circuitry
- Improve filtering and ripple reduction
- Enhance silkscreen labels and layout

---

## 📜 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this project with proper attribution.

See the `LICENSE` file for more details.
