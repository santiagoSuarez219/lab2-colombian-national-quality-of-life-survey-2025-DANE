# Lab 2 — Scientific Computing
## Master in Automation and Industrial Control

**Author:** Santiago Suárez
**Course:** Scientific Computing — Second Laboratory
**Dataset:** Colombian National Quality of Life Survey (ECV) 2025 — DANE

---

## 1. Overview

This laboratory analyzes the **digital divide in Colombia** using microdata from the 2025 Colombian National Quality of Life Survey (ECV). The work links three thematic modules of the survey — Household characteristics (Chapter D), Education (Chapter G) and Information and Communication Technologies (Chapter I) — at the person level (n ≈ 221,043) and answers the following research question:

> **How are educational attainment, sex and geographic area (urban/rural) related to the digital skills of Colombians, and are there significant gaps between socio-educational groups in terms of connectivity and technology use?**

The analysis combines descriptive statistics, formal hypothesis testing (t-tests, ANOVA) and unsupervised learning (k-means clustering with external validation via the Adjusted Rand Index).

---

## 2. Repository structure

```
.
├── Lab2.ipynb                          # Final deliverable (English)
├── README.md                           # This file
├── requirements.txt                    # Python dependencies
└── data/
    ├── clasificacion_variables_inclusion_exclusion.csv   # Variable selection log
    ├── variables_modulos.md                              # Variables by module
    ├── matriz_features_ecv.csv                           # Exported analytical matrix
    ├── hogar.csv                                       # Household module (D)
    ├── educacion.csv                                   # Education module (G)
    ├── tic.csv                                         # ICT module (I)
```

---

## 3. Installation

### 3.1 Requirements
- Python 3.10 or higher.
- pip (or any compatible package manager such as `uv`, `poetry`, `conda`).

### 3.2 Set up a virtual environment

```bash
# from the project root
python3 -m venv .venv
source .venv/bin/activate          # macOS / Linux
# .venv\Scripts\activate           # Windows
pip install -r requirements.txt
```
---
