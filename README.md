<h1 align="center">RD-2027 · Rami Dridi</h1>

<p align="center">
  <b>Electrical engineering student @ ENIT · Embedded systems · FPGA · Edge AI</b><br>
  <i>From thyristor gate pulses to neural networks on silicon.</i>
</p>

<p align="center">
  <a href="https://ramidr45.github.io">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/rami-dridi-103358327/">LinkedIn</a> ·
  <a href="mailto:dridi.rami098@gmail.com">Email</a>
</p>

---

> **DATASHEET** — Rev. 2026.11 · Status: *Active development* · Release: 2027

### 1 · Pin configuration

```text
                    ┌───────────────────────────────┐
        VHDL  ──  1 │●                              │ 16 ──  C / C++
  Zynq / AXI  ──  2 │                               │ 15 ──  Python
       STM32  ──  3 │          R D - 2 0 2 7        │ 14 ──  ROS 2
    FreeRTOS  ──  4 │                               │ 13 ──  YOLO · Hailo NPU
  Emb. Linux  ──  5 │       Rami Dridi · ENIT       │ 12 ──  MATLAB / Simulink
       KiCad  ──  6 │     Electrical Eng. — 2027    │ 11 ──  Docker
     LTspice  ──  7 │                               │ 10 ──  MQTT · InfluxDB · Grafana
         GND  ──  8 │                               │  9 ──  VCC (coffee, 5V ±0.5)
                    └───────────────────────────────┘
```

### 2 · Features

- **Digital design** — RTL in VHDL, custom AXI4-Lite IPs, I²S/I²C audio front-ends on Zynq-7000
- **Real-time firmware** — STM32 + FreeRTOS (tasks, queues, mutexes, notifications), MSP430, ESP32
- **Edge AI** — YOLOv8 on Raspberry Pi 5 with Hailo-8L NPU, keyword spotting on FPGA, GStreamer pipelines
- **Robotics & control** — ROS 2, ballbot stabilisation, state estimation (EKF), model-based design
- **Hardware** — PCB design in KiCad, power electronics from simulation to test bench

### 3 · Typical applications

| Project | What it does | Stack |
|---|---|---|
| [person-following-robot](https://github.com/ramidr45/person-following-robot) | Robot that detects, tracks and follows a person with a single RGB camera | ROS 2 · YOLOv8 (NCNN) · ByteTrack · RPi 5 · Docker · Arduino |
| [hailo8l-object-detection-rpi5](https://github.com/ramidr45/hailo8l-object-detection-rpi5) | Real-time object detection accelerated on an NPU, streamed to a PC | Hailo-8L · YOLOv8 · GStreamer · RTSP/RTP |
| [key-word-spotting-zybo-fpga](https://github.com/ramidr45/key-word-spotting-zybo-fpga) | Spoken-keyword recognition with a VHDL audio chain feeding the ARM core | Zybo Z7 · VHDL · I²S/I²C · AXI · C |
| [bms-digital-twin](https://github.com/ramidr45/bms-digital-twin) | Battery digital twin for state-of-charge estimation | EKF · XGBoost · Python |
| [ramidr45.github.io](https://github.com/ramidr45/ramidr45.github.io) | My portfolio | HTML · CSS · JS |

### 4 · Electrical characteristics

| Parameter | Min | Typ | Max | Unit |
|---|---|---|---|---|
| Curiosity | — | high | saturates | — |
| Abstraction level | transistor | RTL | ROS node | — |
| Time from "it works in simulation" to "it works on the bench" | 1 | 3 | ∞ | days |
| Operating range | lab bench | running track | mountain trail | — |

### 5 · Operating conditions

- 🎓 3rd-year engineering student, **Automation & Industrial Computing**, ENIT (Tunis) — graduating 2027
- 🛠️ Internships at **STEG** (2025) and **ACTIA Engineering Services** (2026)
- 🚀 President of the **ENIT Aerospace Club**
- 🏃 Off-duty: running clubs and hiking

### 6 · Errata

- Known to say *"one more feature"* before a demo. Patch pending.

---

<p align="center"><sub>Open to collaborations on embedded AI, FPGA and robotics — feel free to reach out.</sub></p>
