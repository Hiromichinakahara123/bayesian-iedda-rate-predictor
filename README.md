
# Bayesian Prediction of IEDDA Reaction Rate Constants

This repository contains the Python code and data used for the Bayesian Gaussian Process modeling of second-order rate constants in inverse-electron-demand Diels–Alder (IEDDA) reactions, as described in our manuscript.

## 📄 Manuscript Summary

We employed molecular descriptors from RDKit, PCA-based dimensionality reduction, and a PyMC-based Gaussian Process regression with a lognormal likelihood to predict second-order rate constants (*k₂*) for reactions involving norbornene (NB) and tetrazine (Tz) derivatives.

## 🔧 Repository Structure

```
bayesian-iedda-rate-predictor/
├── README.md               ← Overview and usage guide
├── environment.yml         ← Software dependencies
├── main.ipynb              ← Main notebook for data analysis and modeling
├── data/
│   └── rate_constant_IEDDA.csv  ← Experimental data used for modeling
└── models/
    └── gp_model_final.pkl  ← (optional) saved PyMC model
```

## 🚀 Getting Started

1. Clone this repository:
```
git clone https://github.com/yourusername/bayesian-iedda-rate-predictor.git
cd bayesian-iedda-rate-predictor
```

2. Set up your environment (recommended: `conda`):
```
conda env create -f environment.yml
conda activate iedda-model
```

3. Run the notebook:
Open `main.ipynb` in Jupyter or Google Colab and follow the steps.

## 📦 Dependencies

- Python 3.11+
- PyMC ≥ 5.0
- RDKit ≥ 2023.03
- scikit-learn, pandas, seaborn, matplotlib, arviz

## 📂 Data

The dataset (`rate_constant_IEDDA.csv`) includes:
- SMILES for NB and Tz
- Solvent parameters (dielectric, ET30, temperature)
- Observed rate constants (*k₂*) and errors

## 📬 Contact

For questions, please contact the corresponding author via email.

