# Air-Quality-Project

# How to run
Install dependencies:
   pip install pandas numpy scikit-learn statsmodels matplotlib seaborn

Open Air-Quality-LinearRegression.ipynb in Jupyter Notebook, JupyterLab, or Google Colab.

Run all cells top to bottom. Two early cells (!pip install ucimlrepo and the fetch_ucirepo call) may fail depending on your network but they are harmless leftovers from initial dataset exploration and are not used anywhere. The data is loaded via the URL later. Everything else runs independently of them.

The notebook writes sgd_hyperparameter_log.csv and reg_ols_hyperparameter.csv to its working directory (pre-generated copies are included in this submission for convenience).
