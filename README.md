# Gmax Empirical Prediction App

## Overview
This repository contains a Streamlit-based application for predicting the small-strain shear modulus (Gmax) of granular soils using well-established empirical models.

The application supports:
- Single prediction (manual input)
- Batch prediction (Excel/CSV upload)
- Statistical comparison of predicted vs measured Gmax
- Downloadable results in Excel format

## Models Included
- Hardin and Black (1966)-1
- Hardin and Black (1966)-2
- Oztoprak and Bolton (2013)
- Menq (2003)
- Senetakis and Madhusudhan (2015)
- Liu et al. (2021)
- Wichtmann and Triantafyllidis (2009)

## Input Parameters
- e (void ratio)
- P (confining pressure, kPa)
- Pa (atmospheric pressure, kPa)
- Cu (coefficient of uniformity)
- d50 (median grain size)
- Gmax (MPa, optional for validation)

## How to Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Online App
(After deployment, insert your Streamlit link here)

## Repository Structure
```
app.py
requirements.txt
README.md
LICENSE
CITATION.cff
```

## Authors
Mohammad Jawed Roshan  
António Gomes Correia  
Ionut Dragos Moldovan  
Miguel Azenha  

## Citation
Please use the CITATION.cff file or cite as:

Roshan et al. (2026). Gmax Empirical Prediction App.

## Disclaimer
This tool is intended for research and educational purposes. Users should verify applicability of empirical models before use.
