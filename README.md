PC1 Insufficiency Diagnostic

This repository contains the complete analysis code and figure-generation workflow accompanying the manuscript:

“Dominant Latent Axes Are Necessary but Insufficient to Explain Single-Cell Perturbation Responses.”

The goal of this work is to provide a falsifiable, distribution-aware diagnostic for testing whether a dominant low-dimensional axis (e.g., PC1) is sufficient to explain perturbation outcomes.

Contents

crunchsomethingchallengeV6.ipynb
Main analysis notebook. Reproduces all statistical tests and results reported in the manuscript.

v6_figures.ipynb
Figure-generation notebook. Produces all manuscript figures from precomputed results.

v6_figs/
Output directory containing rendered figures used in the manuscript.

Data

This analysis uses the publicly available single-cell perturbation dataset provided as part of the Broad Obesity Challenge. The notebook assumes access to the dataset in the same format as distributed by the challenge organizers.

No new datasets are introduced in this repository.

Reproducibility

All results in the manuscript can be reproduced by executing the notebooks top to bottom.

No login or credentials are required.

All parameters and thresholds are fixed and documented in the notebooks.

Random seeds are set where stochasticity is unavoidable.

The notebooks are intended to be read and executed as auditable research code, not as a software package.

Scope and Limitations

This repository implements a diagnostic framework, not a predictive model.
It is designed to test representational sufficiency, not to optimize accuracy or forecast unseen perturbations.
