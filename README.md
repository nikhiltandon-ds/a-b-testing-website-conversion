# Website Conversion Optimization using A/B Testing 📊📈

This repository showcases a data-driven A/B testing framework using Python to determine if a new website layout (Design B) drives significantly more user engagement and higher conversion rates than an old layout (Design A).

## Project Structure
- `A_B_Testing_Website_Conversion.ipynb`: The primary, fully-documented Jupyter Notebook featuring analytical steps, data visualization, statistical tests, and comprehensive interpretations.

## Business Challenge
Understanding if changes in a user interface (UI) design translate into tangible business growth can be ambiguous. This project provides an exact statistical validation mechanism using continuous and categorical evaluation techniques.

### Analytical Scope
1. **User Session Durations (Continuous Metrics):** Evaluated via a **Two-Sample Independent T-Test** to verify changes in interaction durations.
2. **User Purchase Action (Categorical Metrics):** Evaluated via a **Chi-Square ($\chi^2$) Test of Independence** to inspect conversions across variants.

## Key Technical Concepts Applied
- **Hypothesis Formulation:** Outlining Null and Alternative statements ($H_0$ and $H_1$).
- **Statistical Significance Evaluation:** Utilizing $p$-values against a set confidence threshold ($lpha = 0.05$).
- **Data Visualizations:** Implementing advanced Kernel Density Estimation (KDE) charts and proportional bar plots via `seaborn` and `matplotlib`.
- **Inference Models:** Running packages from `scipy.stats` for advanced hypothesis evaluations.

## Recommendations
The notebook outlines a statistically valid strategy recommending a full-scale deployment of **Design B** based on clear metric improvements.
