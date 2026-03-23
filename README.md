<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00d4aa,100:00b4d8&height=220&section=header&text=Sanjeev%20Kumar&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=Embedded%20Systems%20Engineer%20%7C%20Digital%20Design%20%7C%20FPGA%20%7C%20Firmware&descSize=16&descColor=cccccc&descAlignY=55&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="mailto:sanjeevsaravanakumarx1@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=00d4aa" alt="Email"/></a>
  <a href="https://linkedin.com/in/sanjusaravananx2-hub"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=00b4d8" alt="LinkedIn"/></a>
  <a href="https://github.com/sanjusaravananx2-hub"><img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=ffffff" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/Location-Leeds,%20UK-0d1117?style=for-the-badge&logo=googlemaps&logoColor=00d4aa" alt="Location"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=00D4AA&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=MSc+Embedded+Systems+Engineering+%40+University+of+Leeds;FPGA+%7C+RTL+Design+%7C+ARM+Cortex+%7C+Real-Time+Systems" alt="Typing SVG" />
</p>

---

## `> whoami`

```c
typedef struct {
    char *name;
    char *degree;
    char *university;
    char *focus[];
} engineer_t;

engineer_t sanjeev = {
    .name       = "Sanjeev Kumar",
    .degree     = "MSc Embedded Systems Engineering (Predicted First Class)",
    .university = "University of Leeds — Graduating Sep 2026",
    .focus      = {
        "FPGA & Digital Design (Verilog HDL)",
        "ARM Cortex-M/A Firmware Development",
        "Hardware-Software Co-Design",
        "Real-Time Signal Processing",
        NULL
    }
};
```

---

## `> cat /proc/skills`

<table>
<tr>
<td width="50%">

### HDL & Digital Design
![Verilog](https://img.shields.io/badge/Verilog_HDL-00d4aa?style=flat-square&logo=v&logoColor=0d1117)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-00b4d8?style=flat-square&logo=v&logoColor=0d1117)
![RTL Design](https://img.shields.io/badge/RTL_Design-0d1117?style=flat-square&logoColor=00d4aa)
![FSM Design](https://img.shields.io/badge/FSM_Design-0d1117?style=flat-square)
![Testbench](https://img.shields.io/badge/Simulation_%26_Testbench-0d1117?style=flat-square)

### FPGA & ASIC Flow
![Quartus](https://img.shields.io/badge/Intel_Quartus_Prime-00b4d8?style=flat-square&logo=intel&logoColor=white)
![SignalTap](https://img.shields.io/badge/SignalTap_II-0d1117?style=flat-square)
![Timing Closure](https://img.shields.io/badge/Timing_Closure-0d1117?style=flat-square)
![ModelSim](https://img.shields.io/badge/ModelSim-0d1117?style=flat-square)

</td>
<td width="50%">

### Languages & Frameworks
![C](https://img.shields.io/badge/C-00d4aa?style=flat-square&logo=c&logoColor=0d1117)
![C++](https://img.shields.io/badge/C++-00b4d8?style=flat-square&logo=cplusplus&logoColor=0d1117)
![Python](https://img.shields.io/badge/Python-00d4aa?style=flat-square&logo=python&logoColor=0d1117)
![MATLAB](https://img.shields.io/badge/MATLAB/Simulink-00b4d8?style=flat-square&logo=mathworks&logoColor=white)

### Embedded Platforms
![STM32](https://img.shields.io/badge/STM32_(Cortex--M)-00d4aa?style=flat-square&logo=stmicroelectronics&logoColor=0d1117)
![Cyclone V](https://img.shields.io/badge/Cyclone_V_SoC_(Cortex--A9)-00b4d8?style=flat-square&logo=intel&logoColor=white)
![Pixhawk](https://img.shields.io/badge/Pixhawk_(PX4/NuttX)-0d1117?style=flat-square)

</td>
</tr>
</table>

### Protocols & Interfaces
<p>
  <img src="https://img.shields.io/badge/AXI4--Lite-00d4aa?style=for-the-badge&logoColor=0d1117" alt="AXI4-Lite"/>
  <img src="https://img.shields.io/badge/SPI-00b4d8?style=for-the-badge" alt="SPI"/>
  <img src="https://img.shields.io/badge/I2C-00d4aa?style=for-the-badge" alt="I2C"/>
  <img src="https://img.shields.io/badge/CAN_2.0B-00b4d8?style=for-the-badge" alt="CAN"/>
  <img src="https://img.shields.io/badge/UART-00d4aa?style=for-the-badge" alt="UART"/>
  <img src="https://img.shields.io/badge/PWM-00b4d8?style=for-the-badge" alt="PWM"/>
</p>

---

## `> ls ~/projects/`

### FPGA-Based Servo Motor Control System
> **Cyclone V DE1-SoC** | Verilog HDL | Intel Quartus Prime 22.1

```
┌──────────────────────────────────────────────────────────────────┐
│                    Cyclone V DE1-SoC                             │
│                                                                  │
│  ┌─────────────┐  ┌───────────┐  ┌────────────┐  ┌───────────┐ │
│  │ PWM Gen     │  │ Sweep FSM │  │ LCD Driver  │  │ AXI4-Lite │ │
│  │ (20-bit ctr)│  │ (multi-   │  │ (ILI9341   │  │ Slave     │ │
│  │ 50 Hz       │◄─┤  state)   │  │  16-bit)   │  │ (4-reg,   │ │
│  └──────┬──────┘  └───────────┘  └────────────┘  │  W1C IRQ) │ │
│         │                                          └─────┬─────┘ │
│         ▼                                                │       │
│    Servo Motor                                     HPS Cortex-A9 │
└──────────────────────────────────────────────────────────────────┘
```
- ~900 lines of synthesizable Verilog across 4 RTL modules — no IP cores or soft processors
- AXI4-Lite slave with write-strobe handling, read-back, and IRQ-pending latch (GIC SPI #72)
- Full RTL flow: simulation → synthesis → P&R → timing closure at **50 MHz**
- On-chip validation using **SignalTap II** logic analyser

---

### CAN Bus Sensor Fusion Platform
> **STM32F4 + Cyclone V SoC** | Verilog | CAN | SPI | I2C | AXI4-Lite

```
 STM32F4 (Sensor Node)          CAN Bus           Cyclone V DE1-SoC
┌───────────────────┐    ┌─────────────────┐    ┌─────────────────────────┐
│ MPU6050 ──┐       │    │                 │    │  FPGA Fabric            │
│ BMP280 ───┤► MCU ─┼──► │  500 kbps       │──► │  SPI Master → CAN      │
│            │       │    │  CAN 2.0B       │    │  Parser → FIR Filter   │
│ Bare-metal │       │    │                 │    │       │ AXI4-Lite      │
│ Interrupt-driven   │    └─────────────────┘    │  HPS (Cortex-A9 Linux) │
└───────────────────┘                            │  Real-time Monitor     │
                                                 └─────────────────────────┘
```
- Custom Verilog IP: SPI master, CAN frame parser, 8-tap FIR filter — **90% latency reduction** vs software
- Heterogeneous SoC pipeline with HW timestamping — **35% throughput improvement**
- Full 2-node CAN 2.0B network with hardware-accelerated signal processing

---

### AI-Driven Thermal Prediction for EV Inverter Power Modules
> **MSc Dissertation — In Progress** | STM32 | Embedded C | Python | MATLAB/Simulink

- Coupled electrothermal IGBT model (10 kHz SPWM, 600V DC, 35A peak) with 4-layer Foster RC network
- Validated within **±3–5°C** of datasheet references
- Deploying lightweight ML model on STM32 via X-CUBE-AI/CMSIS-NN — **95%+ latency reduction**

---

## `> cat /etc/experience`

| Role | Organisation | Period |
|:-----|:------------|:-------|
| **Avionics & Propulsion Engineer** | Gryphon Arrows (IMechE UAS Challenge) | Oct 2025 — Present |
| **Vehicle Dynamics Engineer** | Leeds Gryphon Racing (Formula Student EV) | Oct 2025 — Present |
| **Embedded Systems Engineer** (Industrial Training) | InTrainz, India | Feb 2024 — Sep 2024 |

---

## `> cat /etc/education`

| Degree | Institution | Period |
|:-------|:-----------|:-------|
| **MSc Embedded Systems Engineering** (Predicted First Class) | University of Leeds | 2025 — 2026 |
| **B.Eng Electronics & Communication** (First Class with Distinction) | Sathyabama Institute, Chennai | 2021 — 2025 |

---

## `> cat /etc/certifications`

<p>
  <img src="https://img.shields.io/badge/UK_Amateur_Radio_Foundation_Licence_(M7KVD)-00d4aa?style=flat-square&logo=radio&logoColor=0d1117" alt="Radio"/>
  <img src="https://img.shields.io/badge/GE_Aerospace_Electrical_Engineering_Sim-00b4d8?style=flat-square&logo=ge&logoColor=white" alt="GE"/>
  <img src="https://img.shields.io/badge/Power_Electronics_(Univ._Colorado_Boulder)-00d4aa?style=flat-square&logo=coursera&logoColor=0d1117" alt="Power Electronics"/>
  <img src="https://img.shields.io/badge/MATLAB_Onramp_(MathWorks)-00b4d8?style=flat-square&logo=mathworks&logoColor=white" alt="MATLAB"/>
</p>

---

## `> top -b | head`

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sanjusaravananx2-hub&show_icons=true&theme=react&bg_color=0d1117&title_color=00d4aa&icon_color=00b4d8&text_color=c9d1d9&border_color=30363d&hide_border=false" height="180"/>
  <img src="https://github-readme-streak-stats.herokuapp.com?user=sanjusaravananx2-hub&theme=react&background=0d1117&ring=00d4aa&fire=00d4aa&currStreakLabel=00d4aa&sideLabels=c9d1d9&dates=8b949e&border=30363d" height="180"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sanjusaravananx2-hub&layout=compact&theme=react&bg_color=0d1117&title_color=00d4aa&text_color=c9d1d9&border_color=30363d&langs_count=8" height="160"/>
</p>

---

## `> tail -f /var/log/activity.log`

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=sanjusaravananx2-hub&theme=react-dark&bg_color=0d1117&color=00d4aa&line=00b4d8&point=ffffff&area=true&area_color=00d4aa&hide_border=false" width="95%"/>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00d4aa,100:00b4d8&height=120&section=footer" width="100%"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sanjusaravananx2-hub&style=for-the-badge&color=00d4aa&label=PROFILE+VIEWS" alt="Profile views"/>
</p>

<p align="center">
  <i>💡 "The best interface between hardware and software is a well-defined register map."</i>
</p>
