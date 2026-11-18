# Data Analytics project about air quality

## Overview

A small data analytics project demonstrating best practices for exploratory data analysis (EDA), data cleaning, and insight generation.

## What is EDA?

Exploratory Data Analysis (EDA) is the systematic process of examining, summarizing, and visualizing data before formal modeling or hypothesis testing. It is the first and most critical stage of any data analytics workflow.

## Why EDA Matters

- **Reveals data quality issues** — missing values, duplicates, outliers, inconsistent formats, and type errors become visible early, before they corrupt downstream analysis.
- **Uncovers patterns and relationships** — distributions, correlations, trends, seasonality, and group differences inform which models or metrics are appropriate.
- **Validates assumptions** — statistical tests and models rely on assumptions (normality, linearity, independence); EDA checks whether they hold.
- **Guides feature selection and engineering** — understanding variable behavior leads to better transformations, encoding, and derived features.
- **Detects anomalies and errors** — sensor faults, data entry mistakes, and fraudulent records surface through visual and statistical inspection.
- **Prevents costly mistakes** — issues caught in EDA are far cheaper to fix than errors discovered after modeling or reporting.
- **Builds domain intuition** — analysts gain a feel for the data's structure, scale, and quirks, improving judgment throughout the project.
- **Supports clear communication** — visual summaries make findings accessible to stakeholders and justify decisions.

## Project Structure

```
├── data/
│   ├── raw/            # Original, immutable data
│   └── processed/      # Cleaned and transformed data
├── notebooks/
│   ├── air.ipynb
├── src.txt
├── outputs/
│   └── figures/        # Saved plots and summaries
│   └── reports/        # Saved data for visuls
├── requirements.txt
└── README.md
```

## EDA Workflow in This Project

1. **Data overview** — shape, dtypes, sample rows, summary statistics.
2. **Missing value analysis** — counts, patterns, and imputation strategy.
3. **Univariate analysis** — histograms, box plots, value counts for each variable.
4. **Bivariate analysis** — scatter plots, grouped summaries, correlation heatmaps.
5. **Outlier detection** — IQR and z-score methods with visual inspection.
6. **Data quality report** — documented findings and decisions.

## Requirements

- Python 3.9+
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- jupyter

## Best Practices Followed

- Raw data is never modified.
- Every cleaning step is documented and reproducible.
- Visualizations are saved for reference.
- Findings are summarized before modeling begins.

