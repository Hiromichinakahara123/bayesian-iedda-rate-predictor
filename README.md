# Bayesian Model for IEDDA Rate Constant Prediction

This repository contains the Python code and Jupyter Notebook used to perform molecular descriptor calculations, PCA-based dimensionality reduction, and Bayesian Gaussian Process regression to predict rate constants of IEDDA reactions.

## Files Included

- `Bayesian_IEDDA_Model_with_GP.ipynb`: Main notebook (Google Colab compatible)
- `environment.yml`: Environment file for conda setup

## Data Source

The dataset used in this analysis was extracted from the following publications:

1. Vrabel, M., Kölle, P., Brunner, K. M., Gattner, M. J., López-Carrillo, V., de Vivie-Riedle, R., et al. (2013).  
   *Norbornenes in inverse electron-demand Diels-Alder reactions*. Chem. Eur. J. **19** (40), 13309–13312.  
   DOI: [10.1002/chem.201301838](https://doi.org/10.1002/chem.201301838)

2. Wang, D., Chen, W., Zheng, Y., Dai, C., Wang, K., Ke, B., Wang, B. (2014).  
   *3,6-Substituted-1,2,4,5-Tetrazines: Tuning Reaction Rates for Staged Labeling Applications*.  
   Org. Biomol. Chem. **12** (23), 3950–3955.  
   DOI: [10.1039/c4ob00280f](https://doi.org/10.1039/c4ob00280f)

Due to copyright and reuse restrictions, the dataset file (`rate constant (IEDDAR).csv`) is **not included** in this repository.  
Please consult the original publications for access to the raw data.

## How to Use

1. Clone or download this repository
2. Set up the environment using conda:
   ```bash
   conda env create -f environment.yml
   conda activate iedda-model
   ```
3. Open the notebook and upload the appropriate dataset when prompted.
