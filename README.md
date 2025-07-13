# Reproduction of an Internal Risk Model for Equities – Student-t Calibration and SCR Estimation on CAC 40

This repository contains part of a quantitative research project conducted during an internship at **Generali** as part of the **Master 2 in Mathematical Modeling and Methods in Economics and Finance** at **Université Paris 1 Panthéon-Sorbonne**.

## 📌 Project Overview

**Title:**  
_Reproduction of an internal equity risk model: calibration using the Student-t distribution and SCR estimation on CAC 40 data_

**Objective:**  
To reproduce and validate a Solvency II-compliant internal model for market risk on equity assets, using monthly CAC 40 data. The key goals include:

- Regulatory background analysis (Solvency II & SCR computation)
- Preprocessing of CAC 40 returns and log-return computation
- Calibration of the Student-t distribution via Maximum Likelihood Estimation (MLE)
- Estimation of VaR at 99.5% confidence level
- Comparison with the standard formula SCR
- Model validation: sensitivity analysis, backtesting, and stress scenarios
- Full implementation using **Python on Dataiku**

## 🛠 Work in Progress

The Python code is currently being developed and executed in **Dataiku**, a collaborative data science platform.

### Current Dataiku Flow

Below is the current state of the workflow built in Dataiku:

![Dataiku Workflow](./images/dataiku_flow.png) <C:\Users\mycfr\OneDrive\桌面\Projet-Reproduction d’un modèle interne>

**Explanation:**
- **CAC_40_Time_Series_**: Input dataset (monthly historical data)
- **Python Recipe**: Preprocessing, cleaning, log-return calculation
- **Test**: Output dataset (transformed and enriched)
- **output_folder**: File export for post-processing and reporting

## 📁 Files Included

- `CALIBRATIONDURISQUESDESACTIONS.zip`: Exported Dataiku project archive  
- `compute_test.py`: Partial Python logic (to be added when stable)
- `README.md`: Project description

## 📄 Report

A detailed academic report accompanies this project, including theoretical foundations, methodological choices, and result interpretation. The table of contents includes:

1. Regulatory context (Solvency II, SCR)
2. Data exploration and preprocessing
3. Mathematical modeling (VaR, Student-t)
4. Parameter estimation (MLE)
5. VaR and SCR computation
6. Validation via backtesting, sensitivity, and stress testing

---

*This project is shared for academic and educational purposes.*
