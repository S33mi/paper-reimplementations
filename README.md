# Paper Reimplementations & Reproductions



My personal reproductions and reimplementations of research papers in Python/Jupyter notebooks during my PhD studies.  

Focus: ML, data analysis, optimization, anomaly detection, and EDA tools.



## Current Entries

- **DataPrep.EDA (2021)** — Reimplementing core task-centric EDA features from the SIGMOD 2021 paper "DataPrep.EDA: Task-Centric Exploratory Data Analysis for Statistical Modeling in Python"  

  → [dataprep_eda_reimplementation.ipynb](dataprep_eda_reimplementaion/dataprep_eda_reimplementaion.ipynb)
  
  → [![Open Notebook In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/S33mi/paper-reimplementations/blob/main/dataprep_eda_reimplementaion/dataprep_eda_reimplementaion.ipynb)

  Goal: Build simplified versions of auto-EDA functions (overview stats, distributions, correlations, missing values) without using the original library.

- **Predicting Stock Direction with Random Forest (2016)** — Critical reproduction of Khaidem et al. (arXiv:1605.00003)  
  → [stock_direction_rf_2016.ipynb](stock_direction_rf_2016/stock_direction_rf_2016.ipynb)  
  → [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/S33mi/paper-reimplementations/blob/main/stock_direction_rf_2016/stock_direction_rf_2016.ipynb)

  Goal: Reproduce the reported ~92% accuracy on AAPL and show that the high performance is largely due to data leakage from shuffling a time-series.

More notebooks coming soon!



## Setup

```bash

pip install -r requirements.txt

jupyter notebook
```

OR

Simpily open in Colab no setup required 
