# A Machine Learning Approach for Optimizing Energy and Water Consumption in Smart Homes

Code and outputs for an MSc thesis in Data Analytics, Rochester Institute of Technology (2026).

## Overview

This project uses machine learning to analyze smart-home data:

- **Energy forecasting** using the UCI Appliances Energy Prediction dataset
- **Water diagnostics** using the Zenodo smart-home water-meter dataset

Linear Regression, Ridge Regression, Random Forest and Gradient Boosting are compared with a simple persistence baseline, using a chronological train / validation / test split.

## Contents

- `Smart_Home_Water_Energy_Corrected.ipynb`: main notebook
- `data/`: input CSV files
- `outputs_corrected/`: results, figures and `run_record.json` (run details)

## Data sources

- UCI Appliances Energy Prediction: https://doi.org/10.24432/C5VC8G
- Zenodo Smart Home Dataset: https://doi.org/10.5281/zenodo.4718373

## How to run

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload the `data` folder to `/content/`.
3. Select **Runtime → Run all**.

Results are saved to `outputs_corrected/`.
