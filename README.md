# 🚀 ORION 1 — High-Power Rocket Design & Simulation

**ORION 1** is a single-stage high-power sounding rocket model designed and simulated in **OpenRocket (v24.12)**. Built with a composite carbon-fiber airframe and powered by a hybrid propulsion system, the vehicle is engineered to reach high subsonic velocities and altitudes exceeding 3 kilometers.

---

## 👨‍💻 Developer & Project Info

* **Designer:** Surafel Gashaw (*Leo Xandroveth*)
* **Education:** Class 11 Student at **Memhr Akale Wold**
* **Location:** Ethiopia
* **Design Date:** November 13, 2026
* **Software:** OpenRocket 24.12 (`RK4Simulator` / `BarrowmanCalculator`)

---

## 🛠️ Rocket Specifications

| Parameter | Specification |
| :--- | :--- |
| **Vehicle Name** | ORION 1 |
| **Configuration** | Single-Stage (Sustainer) |
| **Total Length** | 1.48 m (148 cm) |
| **Body Diameter** | 63 mm (0.063 m) |
| **Airframe Material** | Carbon Fiber Composite (`1780 kg/m³`) |
| **Nose Cone** | Von Kármán / Haack Series (0.52 m length, 3 mm wall thickness) |
| **Body Tube** | 0.96 m length, 2 mm wall thickness |
| **Fin Set** | 4 × Trapezoidal Balsa Fins (Root: 18 cm, Tip: 14 cm, Sweep: 9.2 cm, Height: 4.2 cm) |

---

## 🔥 Propulsion System

* **Motor:** RATT Works `K350TR-P`
* **Motor Type:** Hybrid Rocket Motor
* **Dimensions:** 64 mm diameter × 908 mm length
* **Ignition:** Automatic at launch

---

## 📊 Flight Simulation Performance

Simulated under International Standard Atmosphere (ISA) conditions with a 1.0 m launch rod and 2.0 m/s average wind:

![ORION 1 OpenRocket Simulation Graph](orion%201.png)

| Metric | Simulated Value |
| :--- | :--- |
| **Max Altitude (Apogee)** | **3,075.89 m** (~3.08 km / 10,091 ft) |
| **Max Velocity** | **310.48 m/s** (~1,118 km/h) |
| **Max Mach Number** | **Mach 0.92** (High Transonic/Subsonic) |
| **Max Acceleration** | **113.47 m/s²** (~11.6 G) |
| **Time to Apogee** | 23.85 s |
| **Launch Rod Exit Velocity** | 10.57 m/s |
| **Total Flight Time** | 126.71 s |

---

## 📁 Repository Structure

```text
├── ORION_1.ork       # OpenRocket design and simulation file
├── orion 1.png       # OpenRocket flight simulation graph
└── README.md         # Project documentation
