# EGFR QSAR Analysis – Exploratory Data Analysis & Descriptor Calculation

## Overview
This project performs exploratory data analysis (EDA) and molecular descriptor/fingerprint calculation on EGFR bioactivity data.

## Dataset
- Target protein: EGFR
- Total molecules: 97

## Methods Used

### 1. Exploratory Data Analysis
- Distribution analysis of pIC50
- Boxplot comparison between active and inactive compounds
- Mann–Whitney U statistical test
- Correlation heatmap

### 2. Lipinski Descriptors
Calculated using RDKit:
- Molecular Weight (MW)
- LogP
- NumHDonors
- NumHAcceptors

### 3. 2D Molecular Descriptors
- 1444 descriptors generated using PaDEL (PaDELpy)

### 4. Fingerprint Calculation
- PubChem fingerprints (881 bits)
- Generated using PaDELpy

## Key Findings
- NumHAcceptors showed statistically significant difference between active and inactive compounds.
- MW, LogP and NumHDonors were non-significant.

## Tools Used
- Python
- RDKit
- PaDELpy
- Pandas
- Matplotlib / Seaborn
