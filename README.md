#     TEAM NAME: CIRCUIT BREAKERS
# ⏰ 24-Hour Digital Clock Using Discrete Logic ICs

A fully hardware-based **24-hour digital clock** built using **discrete CMOS logic ICs**. This project is being developed during a **2-Day Hackathon** and showcases digital clock design without using any microcontroller or programmable device.

---

## 📌 Project Overview

This project demonstrates the design and implementation of a digital clock using **NE555 Timer** and **CD4026 Decade Counter/7-Segment Driver ICs**.

The entire clock is constructed using discrete electronic components, making it an excellent project for learning digital electronics, counters, clock generation, and sequential circuits.

---

## 🎯 Objectives

- Design a 24-hour digital clock using only discrete ICs.
- Generate clock pulses using the NE555 Timer.
- Count time using CD4026 decade counter ICs.
- Display time on seven-segment displays.
- Document the complete hardware development process.

---

## ✨ Features

- 24-Hour Time Format
- Hardware-Based Clock
- No Microcontroller
- No Programming Required
- Seven Segment Display
- Modular Circuit Design

---

## 🛠 Components Used

| Component | Quantity |
|-----------|---------:|
| NE555 Timer IC | 1 |
| CD4026 Decade Counter IC | 6 |
| Common Cathode 7-Segment Displays | 6 |
| Resistors | Multiple |
| Capacitors | Multiple |
| Push Buttons | Optional |
| Power Supply (5V–9V) | 1 |
| Breadboard & Jumper Wires | As Required |

---

## 🧠 Working Principle

1. The **NE555 Timer** generates a stable clock pulse.
2. The clock pulse is fed to the **CD4026** counter IC.
3. Each CD4026 counts incoming pulses and directly drives a seven-segment display.
4. Cascading multiple CD4026 ICs allows counting seconds, minutes, and hours.
5. Reset logic is implemented using discrete logic to achieve a 24-hour clock cycle.

---

## 📂 Repository Structure

```
Digital_clock/
│
├── README.md
│
├── Documentation/
│   ├── Project_Report.pdf
│   ├── Working_Principle.md
│   ├── Design_Calculations.md
│   └── Component_List.md
│
├── Circuit/
│   ├── Block_Diagram.png
│   ├── Circuit_Diagram.png
│   ├── Breadboard_Layout.png
│   └── Schematic.pdf
│
├── Images/
│   ├── Day_1/
│   ├── Day_2/
│   ├── Testing/
│   └── Final_Output/
│
├── Videos/
│   ├── Timelapse.mp4
│   └── Final_Demo.mp4
│
└── Datasheets/
    ├── NE555.pdf
    └── CD4026.pdf
```

---

# 🚀 Hackathon Progress

## Day 1

- [ ] Research
- [ ] Block Diagram
- [ ] Component Selection
- [ ] NE555 Clock Generator
- [ ] Seconds Counter
- [ ] Initial Testing

## Day 2

- [ ] Minutes Counter
- [ ] Hours Counter
- [ ] Reset Logic
- [ ] Final Wiring
- [ ] Testing
- [ ] Documentation
- [ ] Upload Images
- [ ] Upload Timelapse Video
- [ ] Final Demonstration

---

# 📸 Build Gallery

The complete development process will be documented.

- Project Planning
- Breadboard Assembly
- Wiring Progress
- Debugging
- Final Hardware
- Clock in Operation

---

# 🎥 Timelapse

A complete timelapse of the two-day hackathon build will be uploaded after project completion.

---

# 📚 Documentation

This repository will include:

- Block Diagram
- Circuit Diagram
- Component Selection
- Working Principle
- Design Calculations
- Testing Procedure
- Problems Faced
- Solutions
- Future Improvements

---

# 🔮 Future Improvements

- Alarm Function
- Date Display
- RTC Integration
- PCB Version
- Battery Backup
- Better Enclosure

---

# 📄 License

MIT License

---

# 👨‍💻 Author

**Dinesh P**
**Harish P**
**Poovitha S**

Electronics and Communication Engineering (ECE)

Bannari Amman Institute of Technology
