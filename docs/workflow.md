# Workflow and reproducibility

## Notebook structure

- RISK FACTORS OF STROKE
- BACKGROUND
- ABOUT THE DATA
- 1. Data Preparation
- 1.1 Changing Column Data types
- Changing data types of some columns
- 1.2 Adding New Columns
- 1.3 Checking data skewness
- EXPLORATORY DATA ANALYSIS
- 2.2 Visualisations on Multiple Columns
- Which people are predisposed to stroke - Gender
- Which people are predisposed to stroke - Age
- Which people are predisposed to stroke - Economic Factors
- Which people are predisposed to stroke - Lifestyle Choices

## Required inputs

[Kaggle stroke prediction dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset). Save `healthcare-dataset-stroke-data.csv` beside the notebook. The original notebook describes 5,110 rows and 12 columns.

## Run and interpret

The notebook explores missing values, age groupings, distributions and associations. This is exploratory analysis, not a validated diagnostic model. Saved plots do not establish causality. Dataset provenance and definitions should be reviewed before reusing demographic categories.

## Maintenance verification

A root README, data requirements, execution guide and historical result preview were added. The notebook was checked as Jupyter format. Any preview in the README comes from existing saved output; the full external-data experiment was not rerun. Package installation and original environment compatibility may need adjustment for the historical code. Data, checkpoints and exported outputs are excluded from Git by default.
