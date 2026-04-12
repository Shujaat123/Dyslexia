# Dyslexia Risk Prediction with Machine Learning


This repository contains code, data, and results for the research project based on the dataset introduced in the paper [_Predicting risk of dyslexia with an online gamified test_ by Rello et al. (2020)](https://doi.org/10.1371/journal.pone.0241687). The goal of the project is to establish machine learning baselines and explore advanced ensemble methods for predicting dyslexia risk using behavioral data.


## Repository Structure

Dyslexia/
├── Notebooks/
│   ├── Ensemble.ipynb                      # Advanced ensemble methods and model comparison
│   ├── Ensemble_TSNE_ROC_Curves.ipynb     # t-SNE embeddings and ROC curve visualizations
│   ├── Misc/
│   │   ├── Baseline_ML_Classifiers.ipynb  # Baseline ML model training
│   │   └── DL_Classifiers.ipynb           # Deep learning classifiers
│   └── catboost_info/
│       ├── catboost_training.json
│       ├── learn_error.tsv
│       ├── time_left.tsv
│       └── learn/
│           └── events.out.tfevents
├── Plots & Visuals/
│   ├── euclidean.png
│   ├── manhattan.png
│   ├── f1score_vs_features_mrmr.png
│   ├── roc_curve_165.png
│   ├── roc_curve_all.png
│   ├── tsne_165_features.png
│   ├── tsne_all_features.png
│   └── tsne_roc_plots.png
└── README.md

## Main Notebooks

- [`Ensemble.ipynb`](Notebooks/Ensemble.ipynb): Advanced ensemble methods and model comparison.
- [`Ensemble_TSNE_ROC_Curves.ipynb`](Notebooks/Ensemble_TSNE_ROC_Curves.ipynb): Visualization of t-SNE embeddings and ROC curves for model evaluation.
- [`Misc/Baseline_ML_Classifiers.ipynb`](Notebooks/Misc/Baseline_ML_Classifiers.ipynb): Data loading, preprocessing, and baseline ML model training (Random Forest, SVM, KNN, Gradient Boosting, Bagging, XGBoost, CatBoost, AdaBoost).
- [`Misc/DL_Classifiers.ipynb`](Notebooks/Misc/DL_Classifiers.ipynb): Deep learning classifiers for dyslexia risk prediction.

## Citation

If you use this code or data, please cite:
> A. Khan, and S. Khan, "Feature-Efficient and Interpretable Dyslexia Detection via Soft Voting Ensemble Learning," IEEE Access, 2025, doi: 10.1109/ACCESS.2022.0092316.

## License

This project is for academic research and educational purposes only.

---
