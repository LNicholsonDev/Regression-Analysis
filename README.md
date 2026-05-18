# Ponderosa Pine Climate Regression

Statistical regression analysis of North American Ponderosa Pine field 
survey data, examining how latitude and minimum temperature predict 
stored energy (AET) across sampling sites in the United States.

Biological background informed the variable selection - understanding 
how climatic and geographic factors constrain a conifer's energy budget 
requires domain context that goes beyond fitting a curve to numbers.

---

## Key Finding

Minimum recorded temperature is the strongest predictor of AET 
variability in Ponderosa Pines, outperforming latitude as a standalone 
predictor. The best-fit equation derived from the data:

**ȳ = 37.71 + 0.06(x²)**

The quadratic term reflects a nonlinear relationship between minimum 
temperature and stored energy - a linear model underfit the data.

Full methodology, model evaluation, and interpretation are documented 
in the 11-page statistical report.

---

## Data

Two datasets from a comprehensive North American conifer field survey, 
sourced from Kaggle (Perret and Sax, 2021):

- [`conifer_database_climoccs.csv`](./conifer_database_climoccs.csv) — Climate and occurrence data
- [`itrdb_occs.csv`](./itrdb_occs.csv) — International Tree Ring Data Bank occurrence records

> **Source:** [Comprehensive Conifer Sampling in North America](https://www.kaggle.com/datasets/thedevastator/comprehensive-conifer-sampling-in-north-america)  
> **Study:** [Perret and Sax, 2021 — Zenodo](https://zenodo.org/records/5713338)

* Note: The CSV files contain thousands of entries and are too large to 
preview in GitHub. Download directly or access via the source link above.*

---

## Report

The full statistical report is available as a PDF in this repository.  
Click **"More Pages"** at the bottom of the GitHub PDF viewer to load 
all 11 pages.

[→ View Report](./RegressionAnalysis_StatisticalReport.pdf)

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
