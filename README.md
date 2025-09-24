# Gaussian Processes for Predictive Modeling in Materials Science
## Overview
This repository contains the code and experiments from my Master’s thesis on Gaussian Processes (GPs), exploring both Full and Sparse Variational GPs (SVGPs) for predictive modeling in materials science. The project focuses on two representative systems: a small quantum-simulated water molecule dataset and a large-scale catalytic reaction dataset from methane oxidative coupling. This work demonstrates the versatility of Gaussian Processes for modeling complex scientific data, from small-scale simulations to high-dimensional large datasets, while balancing predictive performance and computational feasibility.
## Data Sources
In the Master's Thesis, two distinct problems were studied, each characterized by its own database:
- The file output_v2.csv corresponds to the dataset for the first problem (water molecule). 
- The file OCM_dataset.csv contains the dataset for the second problem (OCM reactions).
## Contents
The study includes:

- Implementation of Full and Sparse GPs using PyTorch and GPyTorch.

- Evaluation of kernel functions, hyperparameter optimization, and robustness under data scarcity.

- Benchmarking against established regression models like Random Forests and XGBoost.

- A scalability study on the large catalytic dataset, analyzing how training and prediction time grow with dataset size for Full GPs versus SVGPs, highlighting SVGPs’ computational advantages on large datasets.

Note: CODIGO_TFM.ipynb contains the main code and is intended for Google Colab—make sure to adjust the .csv file paths for proper execution.
