# BCG X Customer Churn Analysis

A guided customer-churn analysis from the BCG X Data Science simulation on Forage.

## Main notebook

[Open the integrated customer churn notebook](notebooks/customer_churn_analysis.ipynb)

The notebook combines the updated Task 2-4 materials in one sequence:

1. Customer/pricing data understanding and quality checks.
2. Churn, channel, contract, consumption and margin exploration.
3. Pricing differences, contract-lifecycle features, categorical encoding and numerical transformations.
4. A 75/25 held-out split and a 1,000-tree Random Forest.
5. Confusion matrix, accuracy, precision, recall, F1 and ROC-AUC.
6. Feature importance, interpretation and optional local prediction export.

Model training uses the feature table produced within the notebook, rather than a separate older model-ready CSV. Results are evaluated on held-out customers; class imbalance and recall are considered alongside accuracy.

## Data availability

Use the authorized simulation CSV files in the local `data` folder. The prepared customer input contains earlier pricing variables supplied with the simulation. Raw datasets and customer-level predictions are not redistributed; optional exports go to the ignored `results` folder.

## Attribution

The supplied Task 2 notebook was revised according to answers. Feature engineering and modeling are adapted from the supplied Task 3/4 model-answer notebooks, with BCG X / Forage reference scaffolding retained in context. This repository presents a guided simulation implementation and its integrated execution, rather than claiming an independently designed methodology or employment at BCG.
