# Survival Analysis

If you use this code, please cite the associated Springer Chapter:
"Supreeta Vijayakumar, Giuseppe Magazzù, Pradip Moon, Annalisa Occhipinti and Claudio Angione - A Practical Guide to Integrating Multimodal Machine Learning and Metabolic Modeling".

## Prerequisites

The following dependencies are required in order to complete the survival analysis:

```
python >= 3.5
jupyter notebook
ecos
joblib
numexpr
numpy >= 1.12
osqp
pandas >= 0.25
scikit-learn >= 0.22
scipy >= 1.0
scikit-survival
```

## Running the code

The folder Survival Analysis contains scripts and datasets to run multimodal time-to-event prediction using the Cox-proportional hazards model which takes cancer survival and metabolic data as inputs. 

These files include:

`fluxes.csv` - A complete distribution of metabolic flux values (obtained from running Tissue-Specific FBA or any other flux balance analysis)

`survival_data.csv` - A survival dataset containing time-to-event prediction data for breast cancer

`Survival Analysis.py` - An executable Python script for running survival analysis on any platform, OR -

`Survival Analysis.ipynb` - An IPython notebook that can be used to run survival analysis from Jupyter Notebook

To perform the analysis, simply open `Survival Analysis.ipynb` in Jupyter Notebook and execute the cells from top to bottom OR run `Survival Analysis.py` from any Python platform.

All variables and datasets can be substituted and the script can be adapted according to the users' requirements.
