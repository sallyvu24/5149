## High-distinction requirements

Data Quality Investigation & Exploratory Analysis: Discovers all or most data issues. Uses rigorous statistical evidence (e.g., correlation matrices, hypothesis testing) to prove the influence of features on the loan amount. Deeply analyzes the distribution of missing values.

Preprocessing & Feature Engineering: All imputation, scaling, and encoding steps are perfectly nested within the CV loop, ensuring zero data leakage. Feature engineering is closely tied to the retail lending business (e.g., constructing a debt-to-income ratio), with excellent justification.

Modelling, Validation Strategy: Develops and rigorously compares at least three distinct types of models. The validation strategy (e.g., k-fold CV) flawlessly executes preprocessing within the CV loop. Clearly explains how the final model was chosen based purely on internal CV, explicitly ignoring Public Leaderboard noise.

Results Analysis & Critique: Deeply identifies specific scenarios/populations where the model performs poorly. Delivers a precise critique of how RMSE amplifies large errors by squaring them, discusses whether this property is appropriate for bank lending, and suggests tailored alternative metrics. Clearly articulates improvements needed before deployment.