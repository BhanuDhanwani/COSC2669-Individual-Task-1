cat > README.md <<'EOF'
# COSC2669 Individual Task 1

**Student:** Bhanu Dhanwani  
**Student ID:** S4105617  
**Course:** COSC2669/COSC2816 Case Studies in Data Science  
**Case Study:** People Analytics / Employee Experience

## Overview

This repository contains the analysis completed for Individual Task 1. The case study explores employee retention-related outcomes using two independent HR datasets and connects the analysis to the Associate Data Scientist role at Culture Amp.

Two machine-learning approaches are compared:

- Logistic Regression
- Random Forest

The analysis focuses on class imbalance, model evaluation, interpretability, and the complementary insights provided by the two datasets.

## Datasets

### 1. IBM HR Analytics Employee Attrition

Source:  
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

- 1,470 employee records
- 35 original attributes
- Target: `Attrition`
- Attrition rate: approximately 16.1%
- Fictional/synthetic dataset used for educational analysis

### 2. 2024 APS Employee Census

Source:  
https://data.gov.au/data/dataset/2024-aps-employee-census

- 140,396 survey responses
- 214 original attributes
- Target constructed from Question 40 (intention to leave)
- Final complete-case modelling sample: 132,485 responses
- Positive outcome rate: approximately 31.8%

Raw datasets are not included in this repository. They can be downloaded from the original sources above.

## Repository Structure

```text
.
├── Docs/
│   └── CultureAmp_Associate_Data_Scientist_Job_Ad.pdf
├── Evidence/
│   └── Dataset-selection screenshots
├── Notebooks/
│   └── data_inspection_01.ipynb
├── Outputs/
│   └── Generated figures
├── .gitignore
└── README.md