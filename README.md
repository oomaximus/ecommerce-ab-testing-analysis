# E-Commerce A/B Testing Analysis

## Project Overview

This project investigates the effectiveness of a redesigned e-commerce landing page through an A/B experiment. The objective is to determine whether implementing a new page (treatment) improves customer conversion compared to the existing page (control).

The analysis combines exploratory data analysis, hypothesis testing, and logistic regression to support an evidence-based business recommendation.

## Technologies Used
- Python
- Pandas & NumPy
- Matplotlib
- Statsmodels
- Jupyter Notebook
- Statistical Hypothesis Testing
- Logistic Regression

## Key Findings

| Metric | Result |
|---|---:|
| Control Conversion Rate | 10.53% |
| Treatment Conversion Rate | 15.53% |
| Absolute Conversion Lift | +5.01 percentage points |
| Significance Level | 0.05 |
| Z-Test Statistic | 19.647 |
| P-Value | 3.052 × 10⁻⁸⁶ |

**Conclusion:** The treatment page demonstrated a statistically significant improvement in conversion rates within the analyzed dataset.

Additional regression analysis explored whether geographical differences influenced conversion behavior.

## Methodology

1. Data exploration and cleaning.
2. Descriptive analysis of conversion rates.
3. Statistical hypothesis testing.
4. Logistic regression modeling.
5. Evaluation of country-level interaction effects.
6. Interpretation of findings and business recommendations.

## Project Files

- `Analyze_AB_Test_Results.ipynb` — Complete Python analysis.
- `Analyze_AB_Test_Results.pdf` — Business-facing presentation.
- `ab_data.csv` — Experiment dataset, where redistribution is permitted.

## Business Recommendation

Based on the statistically significant improvement in observed conversion rates, the treatment page is a promising candidate for implementation. Before a full rollout, business stakeholders should also consider implementation costs, experiment validity, and practical impact.

## Acknowledgment

Dataset and original project scenario provided through Udacity's Data Analytics curriculum. Analysis prepared as a personal educational portfolio project.
