# ML-Driven-Prediction-and-Ranking-of-HEDMs

# Installation

Install the required Python libraries:

```bash
pip install rdkit pandas numpy scikit-learn xgboost matplotlib seaborn openpyxl joblib
```

---

# How to Run

1. Clone or download this repository.

2. Open the notebook:

```
HEDM_ML_Project.ipynb
```

using **Jupyter Notebook** or **Google Colab**.

3. Ensure the following input files are placed in the same directory as the notebook:

```
det_dataset_08-02-2022.xlsx
New_Compound_SMILES.csv
```

4. Run all notebook cells sequentially from top to bottom.

---

# Outputs

After execution, the notebook generates:

- Trained models (`.pkl` files)
- `ranked_HEDM_compounds.csv`
- `ranked_unseen_HEDM_compounds.csv`
- Distribution plots for HOF, Density, and VOD
- Predicted vs. Actual performance plots
- Predicted properties and ranking of unseen compounds

# Requirements

- Python 3.10+
- Jupyter Notebook or Google Colab

Required Python libraries:

- RDKit
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- OpenPyXL
- Joblib
