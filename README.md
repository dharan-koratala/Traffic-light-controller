# 🚦 Traffic Light Controller using FSM (Verilog)

## 📌 Project Overview

This project implements a **4-way Traffic Light Controller** using a **Moore Finite State Machine (FSM)** in Verilog HDL.

The system efficiently manages traffic flow at an intersection by controlling signals for all four directions with proper timing and safe transitions.

---

## ⚙️ Features

* 🚥 4-direction traffic control (North, South, East, West)
* 🔁 Moore FSM-based design (output depends only on state)
* ⏱️ Optimized timing sequence for each signal
* ⚡ Glitch-free state transitions
* 🧪 Fully verified using simulation

---

## 🧠 FSM Design

* Each state represents a traffic condition (Green, Yellow, Red)
* State transitions occur based on timing logic
* Only one direction gets Green at a time
* Others remain Red for safety

---

## 🛠️ Tools & Technologies

* Verilog HDL
* Icarus Verilog (Simulation)
* GTKWave (Waveform Viewer)

---

## ▶️ How to Run the Project

```bash
iverilog -o traffic design.v testbench.v
vvp traffic
gtkwave dump.vcd
```

---

## 📸 Simulation Output

*(Add your waveform screenshot below)*

![Waveform](screenshots/output_waveform.png)

---

## 📁 Project Structure

```
traffic-light-controller/
│── design.v
│── testbench.v
│── README.md
│── screenshots/
│     └── output_waveform.png
```

---

## 📈 Key Learnings

* Finite State Machine (FSM) design (Moore model)
* Timing control in digital systems
* Verilog simulation and debugging
* Hardware-oriented problem solving

---

## 🚀 Future Improvements

* Add pedestrian crossing logic
* Adaptive traffic control using sensors
* FPGA implementation

---

## 👨‍💻 Author

**Dharan Koratala**
