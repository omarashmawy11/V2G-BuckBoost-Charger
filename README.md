# 🚗 EV Project 2: Bidirectional Charger with Buck-Boost & SOC-Based Control

This repository contains a MATLAB/Simulink model and technical report for a bidirectional electric vehicle (EV) charging system. The model supports both **Grid-to-Vehicle (G2V)** and **Vehicle-to-Grid (V2G)** modes using a Buck-Boost converter and advanced control strategies, including **dq-axis control**, **PI-regulated PWM switching**, and **SOC-based CC–CV charging logic**.

## 🔧 Features
- ✅ 3-Phase Rectifier with Power Factor Correction (PFC)
- ✅ PLL-based frequency synchronization
- ✅ dq-axis transformation and control
- ✅ Buck-Boost converter with bidirectional energy flow
- ✅ Constant Current–Constant Voltage (CC–CV) charging
- ✅ SOC-based mode switching (CC to CV at 80% SOC)
- ✅ Full battery model with voltage, current, and SOC monitoring

## 📁 Included Files
- `charging_dq.slx` – Complete Simulink model
- `Project_Report.pdf` – Detailed documentation and results
- `Screenshots/` – Simulation visuals and block diagram captures (optional)

## 📊 Key Parameters
| Component            | Value            |
|----------------------|------------------|
| AC Input Voltage     | 380 V (RMS, 3-phase) |
| Battery Capacity     | 20 Ah            |
| Max Charging Voltage | 435 V            |
| Max Charging Current | 50 A             |

> Full parameter table and controller gains included in the report.

## 🛠 Requirements
- MATLAB R2024a or earlier
- Simulink + Simscape Power Systems Toolbox

## 🔗 Related Projects
- 🔋 [EV Project 1: Two-Level On-Board Charger](https://github.com/omarashmawy11/2-Level-On-Board-Charger)

## 📬 Contact
Developed by **Omar Ashmawy**  
www.linkedin.com/in/omar-ashmawy-oa20012376
 – feel free to connect!
