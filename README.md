# Diaporthe_Fol_Analysis

This repository contains the **R script and example data** used for analyzing the effects of *Diaporthe atlantica* and *Fusarium oxysporum* f. sp. *lycopersici* (Fol) inoculation on wheat growth parameters under greenhouse conditions.

## Contents

- `shoot_length_data` – Example dataset (shoot length, cm)
- `analysis_script.R` – General analysis script for all measured parameters
- `README.md` – Repository description

## Description

The analysis pipeline includes:
- Shapiro-Wilk test for normality
- Levene’s test for homogeneity of variances
- Two-way ANOVA with *Diaporthe* and Fol as fixed factors
- Tukey’s HSD post hoc test for pairwise comparisons
- Publication-quality bar plot generation (mean ± SE, significance letters)

## How to Use

1. Clone this repository:
    ```bash
    git clone https://github.com/EricCPereira/diaporthe_fol_analysis.R/tree/main

2. Open `Statistic analysis ANOVA` in RStudio.
3. Run the script to reproduce the analysis and figure.

## Other Parameters

The **same script and pipeline** were used to analyze other parameters in the study, including:
- Shoot and Root Biomass
- Chlorophyll content
- N, P, K, Ca, Mg, Fe, Zn, and Mn
- Relative expression levels AOS1, Pi II, PAL, PR1a, NCED1, Le4, Pti5 
 

Only the input CSV files are different, ensuring consistency across analyses for transparency and reproducibility.

## Citation

If you use this script or workflow, please cite:
> 
