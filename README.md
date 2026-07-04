# gap-adaptive-water-leak-detection
Code and results for missingness-aware machine learning for household water leak screening from cumulative smart-meter data.
# Gap-Adaptive Water Leak Detection

This repository contains the Python/Colab code, result tables, and figures for the manuscript:

**Missingness-Aware Machine Learning for Household Water Leak Screening from Cumulative Smart-Meter Data**

## Dataset

The study uses the public Zenodo dataset:

Smart Meter Water Consumption Measurements  
DOI: 10.5281/zenodo.7506076

The dataset is not redistributed here. Please download it directly from Zenodo.

## Contents

- `gap_adaptive_leak_detection_colab_corrected.ipynb` — main Colab notebook
- `gap_adaptive_leak_detection_colab_corrected.py` — Python script version
- `results/` — model performance and imputation error CSV files
- `figures/` — publication figures
- `requirements.txt` — Python package requirements

## Main analyses

The code reproduces:

- stratified 70/30 model evaluation
- chronological train/test validation
- walk-forward validation
- leave-one-household-out validation
- imputation MAE/RMSE by gap class
- leak magnitude and duration sensitivity analysis

## Citation

If using this code, please cite the associated manuscript.

## Licence

MIT License.
