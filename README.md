# SpuCo
SpuCo Model: Addressing Spurious Correlations in MNIST

This repository contains a PyTorch-based machine learning model that tackles spurious correlations in datasets using the SpuCo framework. The model is applied to the SpuCoMNIST dataset and uses a three-step pipeline to remedy spurious correlations. The SpuCo package is used to ensure robust performance across different groups of data by leveraging group-balancing techniques.

# Features

- SpuCoMNIST Dataset: A modified version of the classic MNIST dataset that introduces spurious correlations, making it a challenging test case for robust model performance.
- ERM Training: Train a model using Empirical Risk Minimization (ERM) to get initial results.
- Clustering: Cluster inputs based on the outputs generated during the ERM phase.
- Group-Balancing: Retrain the model using a group-balanced approach to ensure fairness across different clusters.
- R obustness to Spurious Correlations: The method mitigates spurious correlations, improving model generalization on unbiased test sets.
