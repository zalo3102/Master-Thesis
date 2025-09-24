# Gaussian Processes for Predictive Modeling in Materials Science
## Overview
This repository contains the code and experiments from my Master’s thesis on Gaussian Processes (GPs), exploring both Full and Sparse Variational GPs (SVGPs) for predictive modeling in materials science. The project focuses on two representative systems: a small quantum-simulated water molecule dataset and a large-scale catalytic reaction dataset from methane oxidative coupling. This work demonstrates the versatility of Gaussian Processes for modeling complex scientific data, from small-scale simulations to high-dimensional large datasets, while balancing predictive performance and computational feasibility.
## Repository Contents

- CODIGO_TFM.ipynb – Main notebook implementing Full and Sparse Variational Gaussian Processes using PyTorch and GPyTorch. Intended for Google Colab; adjust .csv file paths as needed.

- output_v2.csv – Dataset for the first problem: small quantum-simulated water molecule.

- OCM_dataset.csv – Dataset for the second problem: large-scale methane oxidative coupling (OCM) reactions.

- docs/Thesis.pdf – Full Master’s thesis in PDF format, including methodology, theoretical background, results, figures, and detailed analyses.
## Contents
The study includes:

- Implementation of Full and Sparse GPs using PyTorch and GPyTorch.

- Evaluation of kernel functions, hyperparameter optimization, and robustness under data scarcity.

- Benchmarking against established regression models like Random Forests and XGBoost.

- A scalability study on the large catalytic dataset, analyzing how training and prediction time grow with dataset size for Full GPs versus SVGPs, highlighting SVGPs’ computational advantages on large datasets.

