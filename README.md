# Dyslexia Risk Prediction with Machine Learning

This repository contains code, data, and results for the research project based on the dataset introduced in the paper [_Predicting risk of dyslexia with an online gamified test_ by Rello et al. (2020)](https://doi.org/10.1371/journal.pone.0241687). The goal of the project is to establish machine learning baselines and explore advanced ensemble methods for predicting dyslexia risk using behavioral data.

## Contents

- **Notebooks**: Jupyter notebooks for data preprocessing, baseline ML classifiers, ensemble methods, t-SNE, and ROC curve analysis.
- **Plots & Visuals**: Visualizations of results, including feature selection, t-SNE, and ROC curves.

## Main Notebooks

- [`Baseline_ML_Classifiers.ipynb`](Dyslexia/Notebooks/Baseline_ML_Classifiers.ipynb): Data loading, preprocessing, and baseline ML model training (Random Forest, SVM, KNN, Gradient Boosting, Bagging, XGBoost, CatBoost, AdaBoost).
- [`Ensemble.ipynb`](Dyslexia/Notebooks/Ensemble.ipynb): Advanced ensemble methods and model comparison.
- [`Ensemble_TSNE_ROC_Curves.ipynb`](Dyslexia/Notebooks/Ensemble_TSNE_ROC_Curves.ipynb): Visualization of t-SNE embeddings and ROC curves for model evaluation.

## Citation

If you use this code or data, please cite:
> A. Khan, M. S. Ibrahim, A. Wahab, N. Ahmed, and S. Khan, “Feature-Efficient and Interpretable Dyslexia Detection via Soft Voting Ensemble Learning,” IEEE Access, 2025, doi: 10.1109/ACCESS.2022.0092316.

## License

This project is for academic research and educational purposes only.

---