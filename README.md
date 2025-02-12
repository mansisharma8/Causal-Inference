# Causal Inference for Data Science

## Overview
This project focuses on **causal inference**, a fundamental technique in data science used to determine cause-and-effect relationships from observational data. The project implements various causal inference methods, including **propensity score matching, instrumental variables, and difference-in-differences**, to analyze treatment effects.

## Dataset
- **Source:** Publicly available economic, healthcare, and social science datasets.
- **Features:** Treatment indicators, outcome variables, covariates for confounding control.
- **Preprocessing:**
  - Handled missing values and outliers.
  - Standardized continuous variables for better model performance.

## Methodology
1. **Exploratory Data Analysis (EDA):** 
   - Visualized distributions and relationships between treatment and outcome.
   - Assessed confounding variables using correlation matrices.

2. **Causal Inference Techniques:**
   - **Propensity Score Matching (PSM):** Estimated treatment effects by matching treated and untreated units.
   - **Instrumental Variables (IV):** Used for causal estimation when treatment is endogenous.
   - **Difference-in-Differences (DiD):** Compared treatment and control groups over time.
   - **Regression Discontinuity Design (RDD):** Identified causal effects around cutoff points.

3. **Model Evaluation & Interpretation:**
   - Conducted hypothesis testing for causal relationships.
   - Assessed robustness using placebo tests and sensitivity analysis.

## Results & Insights
- Demonstrated the effectiveness of **PSM and DiD** in estimating causal effects.
- Identified significant treatment impacts in various real-world scenarios.
- Highlighted the importance of controlling for confounding variables in observational studies.

## Technologies Used
- **Programming Languages:** Python
- **Libraries & Tools:** `causalml`, `econml`, `statsmodels`, `scikit-learn`, `pandas`, `matplotlib`
- **Statistical Techniques:** ATE, ATT estimation, hypothesis testing, bootstrapping
- **Visualization:** Causal effect plots, balance diagnostics

## Future Improvements
- Implement **causal deep learning models** for complex treatment effects.
- Integrate **synthetic control methods** for improved counterfactual analysis.
- Apply **causal inference techniques** to real-world policy evaluation.

