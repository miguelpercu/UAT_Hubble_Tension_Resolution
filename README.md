# UAT_Hubble_Tension_Resolution
Resolviendo la Tension de Habble con UAT de Percudani Miguel Angel
# UAT Hubble Tension Resolution

![UAT Framework](https://img.shields.io/badge/Framework-UAT-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)

## 📖 Overview

This repository contains the complete implementation and analysis for the **Unified Applicable Time (UAT) Framework**, a novel approach to resolving the Hubble tension through quantum gravitational effects derived from Loop Quantum Gravity (LQG).

The UAT framework introduces a fundamental parameter `k_early` that modifies early universe expansion history, reducing the sound horizon `r_d` by approximately 4.1% while maintaining the locally measured `H₀ = 73.0 km/s/Mpc`.

## 🎯 Key Results

- **Hubble Constant**: H₀ = 73.00 ± 0.82 km/s/Mpc (SH0ES value maintained)
- **Sound Horizon**: r_d = 141.00 ± 1.1 Mpc (4.1% reduction from Planck)
- **Early Universe Parameter**: k_early = 0.967 ± 0.012
- **Statistical Improvement**: Δχ² = +38.41 (vs ΛCDM optimal)
- **Bayesian Evidence**: ln(B₀₁) = 12.64 (decisive evidence for UAT)

## 📁 Repository Structure
UAT_Hubble_Tension_Resolution/
├── 📄 Manuscript/
│ ├── UAT_Hubble_Tension_Paper.tex # Main LaTeX manuscript
│ ├── references.bib # Bibliography
│ └── figures/ # All manuscript figures
│ ├── UAT_MCMC_corner_plot.png # Fig 1: Parameter distributions
│ ├── parameter_optimization_consistent.png # Fig 2: k_early optimization
│ ├── UAT_BAO_comparison_consistent.png # Fig 3: BAO comparison
│ └── model_residuals_consistent.png # Fig 4: Residual analysis
├── 💻 Code/
│ ├── UAT_Hubble_Tension_Resolution.py # Main analysis code
│ ├── UAT_MCMC_Analysis.py # Bayesian MCMC implementation
│ └── requirements.txt # Python dependencies
├── 📊 Results/
│ ├── tables/
│ │ ├── final_results_summary_consistent.csv # Model comparison
│ │ ├── detailed_predictions_consistent.csv # Predictions vs observations
│ │ ├── future_predictions_consistent.csv # Future survey predictions
│ │ └── bao_observational_data.csv # BAO observational data
│ └── analysis/
│ ├── physical_interpretation_consistent.txt # Physical interpretation
│ ├── executive_summary_consistent.txt # Executive summary
│ └── analysis_configuration_consistent.txt # Configuration details
└── 📚 Data/
└── bao_observational_data.csv # BAO data from BOSS/eBOSS

python UAT_Hubble_Tension_Resolution.py
python UAT_MCMC_Analysis.py

