# ☀️ Research on Perovskite Solar Cell (Cs₂TiBr₆)

![Domain](https://img.shields.io/badge/Domain-Renewable%20Energy%20%7C%20Solar%20Research-blue)
![Material](https://img.shields.io/badge/Material-Lead--Free%20Perovskite%20(Cs₂TiBr₆)-success)
![Simulation](https://img.shields.io/badge/Simulation-SCAPS--1D-orange)
![Status](https://img.shields.io/badge/Status-Research%20Project-purple)

---

## 🧾 Abstract

The rapid advancement of perovskite solar cells (PSCs) has positioned them as promising candidates for next-generation photovoltaic technologies. However, the presence of toxic lead (Pb) remains a significant challenge for large-scale deployment. This research investigates **Cs₂TiBr₆**, a **lead-free double perovskite**, as an environmentally sustainable absorber material for high-performance solar cells.

Numerical simulations were carried out using **SCAPS-1D** to evaluate the photovoltaic performance of Cs₂TiBr₆-based devices. The study systematically analyzes the influence of absorber thickness, defect density, and charge transport layers on key device parameters such as **open-circuit voltage (V<sub>OC</sub>)**, **short-circuit current density (J<sub>SC</sub>)**, **fill factor (FF)**, and **power conversion efficiency (PCE)**. The obtained results demonstrate that optimized Cs₂TiBr₆-based solar cells can achieve efficiencies comparable to reported state-of-the-art lead-free PSCs, highlighting their strong potential for eco-friendly photovoltaic applications.

---

## 🎯 Research Objectives

- Investigate **Cs₂TiBr₆** as a **non-toxic, lead-free perovskite absorber**
- Perform **numerical device simulation using SCAPS-1D**
- Extract and analyze **electrical and photovoltaic parameters**
- Compare obtained results with **published literature benchmarks**
- Assess feasibility for **high-efficiency and sustainable PSCs**

---

## 🔬 Device Simulation Methodology

- **Simulation Tool:** SCAPS-1D  
- **Device Architecture (Generic):**  
  `Front Contact / ETL / Cs₂TiBr₆ Absorber / HTL / Back Contact`
- **Optimization Parameters:**
  - Absorber thickness
  - Defect density
  - Band alignment
  - Transport layer properties

---

## 📂 Repository Structure

```
Research-on-Perovskite-Solar-Cell-Cs2TiBr6/
│
├── ALL FILES ( Editable Format )/ # Editable SCAPS & analysis files
├── DOCUMENTS/ # Synopsis, reports, research notes
├── GRAPHS/ # J–V curves, QE plots, trends
├── REFERENCE PAPER/ # Published literature PDFs
├── SCAPS_RESULTS/ # Raw SCAPS output files
├── SCAPS_RESULTS_DATA_EXCEL_SHEET/ # Numerical data tables
└── README.md

```


---

## 📊 Numerical Results (SCAPS-1D Simulation)

### 🔢 Optimized Device Performance Metrics

| Parameter | Symbol | Value |
|--------|--------|-------|
| Open-Circuit Voltage | V<sub>OC</sub> | **1.36 V** |
| Short-Circuit Current Density | J<sub>SC</sub> | **24.31 mA/cm²** |
| Fill Factor | FF | **90.52 %** |
| Power Conversion Efficiency | PCE | **29.78 %** |
| Absorber Thickness | — | **≈ 600 nm** |
| Operating Temperature | — | **300 K** |

> These values correspond to the optimized Cs₂TiBr₆ absorber configuration obtained via SCAPS-1D simulations.

---

## 📈 Simulation Results & Plots

### 🔹 J–V Characteristics
<img src="GRAPHS/JV_Curve.png" alt="J-V Curve" width="650"/>

### 🔹 Quantum Efficiency (QE)
<img src="GRAPHS/Quantum_Efficiency.png" alt="Quantum Efficiency Curve" width="650"/>

### 🔹 Performance Parameter Trends
<img src="GRAPHS/Parameter_Optimization.png" alt="Parameter Optimization Graphs" width="650"/>

*(Graphs are available in the **GRAPHS/** folder and generated using SCAPS output data.)*

---

## 📚 Benchmark Comparison with Literature

| Study | Material | PCE (%) | V<sub>OC</sub> (V) | FF (%) |
|-----|---------|---------|------------------|--------|
| Reported Literature | Cs₂TiBr₆ | 29.19 – 31.02 | 1.33 – 1.40 | 90.4 – 90.7 |
| **This Work (SCAPS)** | **Cs₂TiBr₆** | **29.78** | **1.36** | **90.52** |

### 🔍 Comparative Analysis

- The simulated PCE (**29.78%**) lies **well within the upper range** of reported literature values.
- Excellent **fill factor (>90%)** confirms efficient charge transport and minimal recombination.
- Achieved **V<sub>OC</sub> of 1.36 V** indicates strong absorber quality and band alignment.
- Results validate **Cs₂TiBr₆ as a competitive lead-free alternative** to conventional Pb-based perovskites.

---

## 🧠 Key Research Insights

- Cs₂TiBr₆ demonstrates **high photovoltaic potential** despite being lead-free.
- Device efficiency is highly sensitive to **defect density and interface optimization**.
- SCAPS-1D proves effective for **predictive modeling and performance tuning**.
- The results support further **experimental and fabrication-level exploration**.

---

## 📌 Future Scope

- Experimental fabrication and validation
- Interface defect engineering
- Stability and degradation analysis
- Tandem and multi-junction integration

---

## 👤 Author

**Priyanshu Aggarwal**  
Electronics & Communication Engineering  

📧 Email: Priyanshuaggarwal.in@gmail.com  
🔗 LinkedIn: https://linkedin.com/in/priyanshu1201  
💻 GitHub: https://github.com/AggarwalPriyanshu  

---

⭐ *If you find this research valuable, feel free to star the repository and share it.*
