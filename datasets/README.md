# datasets
This folder contains the raw datasets used in the project. Each file corresponds to a different problem domain and serves as the primary data source for the associated analyses.

## Files
1. **output_v2.csv** - Dataset for the first problem, describing a deformed water molecule through two internal degrees of freedom:

- **Bending angle (ω)**

- **Asymmetric stretching coordinate (ν′)**

These parameters define the molecular deformation space and allow the calculation of the target variables in the dataset (energy and dipole moments) using the Partridge–Schwenke model.

**Reference:**
V. L. Deringer, A. P. Bartók, N. Bernstein, D. M.Wilkins, M. Ceriotti, and G. Csányi, Gaussian process regression for materials and molecules, Chemical Reviews 121, 10073 (2021).

2. **OCM_dataset.xlsx** - Dataset for the second problem, focused on oxidative coupling of methane (OCM) reactions.
This file includes reaction conditions, catalyst information, performance metrics, and other variables relevant to analyzing OCM reaction behavior. In this case, the target variable was the OCM reaction yield.

**Reference:**
S. Mine, M. Takao, T. Yamaguchi, T. Toyao, Z. Maeno, S. Hakim Siddiki, S. Takakusagi, K.-i. Shimizu, and I. Takigawa, Analysis of updated literature data up to 2019 on the oxidative coupling of methane using an extrapolative machine-learning method to identify novel catalysts. chemcatchem. 2021; 13 (16): 3636-3655, DOI: https://doi.org/10.1002/cctc 202100495.
