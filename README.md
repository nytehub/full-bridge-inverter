# 🔌 Full-Bridge Inverter - My 12th Class Electronics Project

This project is about building a basic circuit called a **Full-Bridge Inverter**. Its main job is to convert everyday battery power (DC - Direct Current) into the type of power used in homes (AC - Alternating Current). This is a cool beginner-friendly project for understanding how electricity can be switched around to create different kinds of power—just like in big solar systems or UPS devices!

---

## 📝 Project Summary

Imagine you have a battery (DC power) but want to power a small AC light bulb. That's where an inverter comes in!  
This project uses a special arrangement of electronic switches, called an **H-Bridge**, to rapidly turn the DC power on and off in different directions. This switching creates a **square-wave (or almost sine-wave)** AC output.

The goal is to see how we can make our own AC power from a DC source.

---

## 🔧 What It Does

- **Changes Battery Power (DC) to Wall Socket Power (AC):** Takes a steady flow of electricity (like from a 12V battery) and turns it into a back-and-forth AC flow.
- **Creates a "Square Wave" Output:** Unlike a smooth sine wave at home, this basic inverter makes a blocky, on-off-on-off wave.
- **Uses a Smart "H" Shape:** The H-bridge configuration allows current to flow in both directions.
- **Controlled by PWM (Pulse Width Modulation):** Fast ON/OFF pulses control the switches—done using an Arduino or a 555 Timer.

---

## 🛠 Technologies & Components Used

| Component             | Simple Purpose                                                                 |
|----------------------|---------------------------------------------------------------------------------|
| **MOSFETs**           | High-speed electronic switches that form the H-Bridge.                         |
| **Driver Circuits**   | Amplify control signals to fully switch MOSFETs ON/OFF.                        |
| **PWM Controller**    | Generates fast ON/OFF signals (e.g., Arduino or 555 Timer).                    |
| **LC Filter (Optional)** | Smooths square wave into more sine-like wave using coils & capacitors.     |
| **DC Power Supply**   | Powers the circuit (e.g., 12V battery or adapter).                             |
| **Load**              | Device powered by AC output (e.g., light bulb, fan).                           |
| **Resistors & Capacitors** | Basic circuit components for current control and timing.                 |
| **Breadboard / PCB**  | For assembling and connecting components.                                      |

---

## 🧠 What I Learned / Showcased

- How to convert **DC to AC** using electronic components.
- Working of an **H-Bridge circuit**.
- Basics of **Pulse Width Modulation (PWM)**.
- How **MOSFETs** control high power with small signals.
- Role of **driver circuits** in power switching.
- (Optional) Using **filters** to smooth electrical signals.
- Practical exposure to **power electronics** concepts.

---

## 🖼️ Suggested Folder Structure for GitHub Repo

```yaml
full-bridge-inverter/
├── README.md
├── circuit/
│   └── schematic.png
```

### 📁 `circuit/schematic.png`

Contains the circuit diagram showing how all components are connected.

---
