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
├── environment.yml                     # Conda environment spec (recommended)
├── requirements.txt                    # Pip dependency list (fallback)
└── data/
    ├── clasificacion_variables_inclusion_exclusion.csv   # Variable selection log
    ├── variables_modulos.md                              # Variables by module
    ├── matriz_features_ecv.csv                           # Exported analytical matrix
    ├── hogar.csv                                         # Household module (D)
    ├── educacion.csv                                     # Education module (G)
    └── tic.csv                                           # ICT module (I)
```

---

## 3. Installation (conda)

The project is set up to run inside a **conda environment** named `lab2-ecv`, built with **Python 3.12.13** — the same interpreter used to develop the notebook. The environment is fully described in [`environment.yml`](environment.yml).

### 3.1 Requirements
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/) (any recent version).

### 3.2 Create the environment

From the project root:

```bash
conda env create -f environment.yml
```

This creates an isolated environment called `lab2-ecv` with Python 3.12 and all required scientific libraries (pandas, numpy, scipy, scikit-learn, matplotlib, seaborn, jupyter, ipykernel, openpyxl).

### 3.3 Activate the environment

```bash
conda activate lab2-ecv
```

You should see the prompt change to `(lab2-ecv) ...`. Verify the Python version:

```bash
python --version    # Python 3.12.13
```

### 3.4 Register the Jupyter kernel (optional)

If you plan to open the notebook in Jupyter Lab / Notebook / VS Code and want the environment to appear as a selectable kernel:

```bash
python -m ipykernel install --user --name=lab2-ecv --display-name "Python (Lab 2 ECV)"
```

### 3.5 Updating the environment

If the `environment.yml` file changes later, sync the existing environment with:

```bash
conda env update -f environment.yml --prune
```

### 3.6 Removing the environment

```bash
conda deactivate
conda env remove -n lab2-ecv
```

---

## 4. Running the notebook

With the environment activated:

```bash
# from the project root, with (lab2-ecv) active
jupyter notebook Lab2.ipynb
# or, equivalently
jupyter lab Lab2.ipynb
```

In **VS Code**, open `Lab2.ipynb` and select the kernel **Python (Lab 2 ECV)** (or `lab2-ecv` if you skipped step 3.4) from the kernel picker in the top right.

Run all cells top to bottom (`Kernel → Restart & Run All` in Jupyter, or `▶▶` in VS Code). The total runtime is on the order of **2–3 minutes** on a recent laptop, with the k-means sweep being the most time-consuming step.

---
