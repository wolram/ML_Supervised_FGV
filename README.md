# ML_Supervised_FGV — Exploratory Data Analysis for Supervised Machine Learning (FGV)

Course materials for the **Supervised Machine Learning Techniques** class at FGV (Fundacao Getulio Vargas), taught by Professor Ana Gularte. This repository contains a comprehensive Exploratory Data Analysis (EDA) workflow using the UCI Automobile dataset.

## Features

- Full EDA pipeline: data characterization, descriptive statistics, and distribution analysis
- Variable classification (nominal, ordinal, discrete, continuous) with domain context
- Univariate analysis: frequency tables, histograms, boxplots, pie charts, KDE plots
- Normality testing with Shapiro-Wilk
- Multivariate analysis: covariance, Pearson correlation, scatter plots, heatmaps
- Hierarchical clustering heatmap (clustermap with dendrograms)
- Principal Component Analysis (PCA) with variance explained curves and loading interpretation
- PCA visualization colored by target variable (symboling / insurance risk)
- Automated EDA reports with ydata-profiling and Sweetviz

## Tech Stack

- Python 3
- pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn (PCA, StandardScaler, SimpleImputer)
- SciPy (Shapiro-Wilk test)
- ydata-profiling, Sweetviz
- Google Colab

## Dataset

**Automobile** (UCI Machine Learning Repository) — contains characteristics of 205 cars (make, fuel type, body style, engine specs, price, etc.) and their insurance risk rating (`symboling`).

- Source: [UCI Automobile Dataset](https://archive.ics.uci.edu/ml/datasets/Automobile)
- File: `imports85.csv`
- Data dictionary: `Dicionario_Variaveis_Automobile_imports85.pdf`

## Getting Started

1. Open `Analise_Exploratoria_de_Dados.ipynb` in Google Colab
2. Upload `imports85.csv` to your Google Drive (adjust the path in the notebook)
3. Run all cells sequentially

Alternatively, use the exported Python script `analise_exploratoria_de_dados.py`.

## License

MIT
