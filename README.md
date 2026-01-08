# 🔬 Research on Lead-Free Perovskite Solar Cell (Cs₂TiBr₆)

![Domain](https://img.shields.io/badge/Domain-Perovskite%20Solar%20Cells-blue)
![Simulation](https://img.shields.io/badge/Simulation-SCAPS--1D-orange)
![Material](https://img.shields.io/badge/Material-Cs2TiBr6-green)
![Type](https://img.shields.io/badge/Type-Numerical%20Research-purple)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **Numerical Simulation & Performance Optimization of Lead-Free Perovskite Solar Cells using SCAPS-1D**

This repository contains a **detailed numerical research study** on a **lead-free double perovskite solar cell based on Cs₂TiBr₆**, focusing on **device architecture optimization**, **transport layer engineering**, and **performance evaluation** using the **SCAPS-1D solar cell simulator**.

The work addresses environmental concerns of lead-based perovskites while achieving **competitive photovoltaic performance** through careful material and interface optimization.

---

## 🧾 Abstract

Lead-free perovskite solar cells have emerged as promising alternatives to conventional lead-based photovoltaics due to their environmental compatibility and long-term stability. In this work, a Cs₂TiBr₆-based perovskite solar cell is numerically modeled and optimized using the SCAPS-1D simulator. Various device architectures incorporating different electron and hole transport layers are investigated. The optimized structure **Au / CuAlO₂ / Cs₂TiBr₆ / IGZO / FTO** demonstrates a maximum **power conversion efficiency (PCE) of 19.53%**. The performance enhancement is attributed to improved energy band alignment, reduced recombination losses, and efficient charge carrier extraction. The results highlight Cs₂TiBr₆ as a strong candidate for next-generation lead-free photovoltaic devices.

---

## 🎯 Research Objectives

- Design and simulate a **lead-free perovskite solar cell**
- Optimize **HTL and ETL material combinations**
- Analyze **SCAPS-1D numerical outputs**
- Identify the **best-performing device configuration**
- Compare results with **reported literature benchmarks**

---

## 🧱 Optimized Device Architecture

### ✅ Best Performing Structure

```

Au / CuAlO₂ / Cs₂TiBr₆ / IGZO / FTO

```


**Layer Details**
- **Absorber:** Cs₂TiBr₆  
- **Hole Transport Layer (HTL):** CuAlO₂  
- **Electron Transport Layer (ETL):** IGZO  
- **Front Contact:** FTO  
- **Back Contact:** Au  

---

## 🛠️ Simulation Environment

- **Simulation Tool:** SCAPS-1D  
- **Illumination:** AM 1.5G  
- **Operating Temperature:** 300 K  
- **Absorber Thickness:** ≈ 600 nm  
- **Analysis Performed:**  
  - J–V Characteristics  
  - Quantum Efficiency (QE)  
  - Energy Band Diagrams  

---

## 📊 Numerical Results (Best Configuration)

> ✔ Extracted directly from  
> `SCAPS_RESULTS_DATA_EXCEL_SHEET / MINOR_MAIN_TABLE.xlsx`

| Parameter | Symbol | Value |
|---------|--------|------|
| Open-Circuit Voltage | V<sub>OC</sub> | **1.123 V** |
| Short-Circuit Current Density | J<sub>SC</sub> | **23.54 mA/cm²** |
| Fill Factor | FF | **73.88 %** |
| Power Conversion Efficiency | PCE (η) | **19.53 %** |
| Device Architecture | — | **Au / CuAlO₂ / Cs₂TiBr₆ / IGZO / FTO** |
| Operating Temperature | — | **300 K** |

✔ Best efficiency among all simulated configurations  
✔ Data is **simulation-backed (not random)**  

---

## 📈 Key Performance Insights

- **CuAlO₂ HTL** significantly reduces hole recombination
- **IGZO ETL** provides favorable band alignment and electron mobility
- Optimized interfaces improve **Fill Factor and Voc**
- Alternative transport layers showed reduced efficiency due to higher interfacial losses

---

## 🖼️ SCAPS Simulation Results

All simulation outputs are stored **exactly as per repository structure**.

### Available Outputs
- J–V Characteristics  
- Quantum Efficiency (QE) plots  
- Energy Band Diagrams  

📁 **Folder References**

```

GRAPHS/
├── JV_Curves/
├── QE_Plots/
└── Band_Diagrams/

SCAPS_RESULTS/
└── Raw_SCAPS_Output_Files

```


---

## 📚 Comparison with Literature

Previously reported Cs₂TiBr₆-based lead-free perovskite solar cells typically demonstrate efficiencies in the range of **3–12%**, limited by carrier transport and recombination losses.

The **19.53% PCE** achieved in this work represents a **significant improvement**, emphasizing the importance of transport layer optimization and interface engineering in lead-free perovskite devices.

---

## 📂 Repository Structure (Verified)

```

Research-on-Perovskite-Solar-Cell-Cs2TiBr6/
│
├── ALL FILES ( Editable Format )/
│ ├── Editable_Presentations
│ └── Editable_Documents
│
├── DOCUMENTS/
│ ├── Project_Report
│ └── Synopsis
│
├── GRAPHS/
│ ├── JV_Curves
│ ├── QE_Plots
│ └── Band_Diagrams
│
├── REFERENCE PAPER/
│ └── Research_and_Review_Papers
│
├── SCAPS_RESULTS/
│ └── SCAPS_Output_Files
│
├── SCAPS_RESULTS_DATA_EXCEL_SHEET/
│ └── MINOR_MAIN_TABLE.xlsx
│
└── README.md

```


---

## 🔮 Future Scope

- Experimental validation of simulated architecture  
- Interface defect density and trap-state analysis  
- Temperature-dependent performance study  
- Tandem and multilayer device integration  

---

## 👤 Author

**Priyanshu Aggarwal**  
Electronics & Communication Engineering  

📧 Email: Priyanshuaggarwal.in@gmail.com  
🔗 LinkedIn: https://linkedin.com/in/priyanshu1201  
💻 GitHub: https://github.com/AggarwalPriyanshu  

---

⭐ If you find this repository useful, feel free to star it!
