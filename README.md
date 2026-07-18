# Product Experimentation & A/B Testing Engine

An automated quantitative framework built to calculate baseline sample sizes, simulate user transaction data, and perform hypothesis testing for platform feature rollouts.

## Features
* **Power Analysis:** Computes optimal sample sizes based on minimum detectable effects (MDE), baseline conversions, and 80% statistical power.
* **Hypothesis Testing Engine:** Runs two-sample Z-tests and Chi-squared tests of independence to evaluate conversion lifts.
* **Data Visualization:** Utilizes Seaborn to output presentation-ready bar charts complete with 95% binomial confidence intervals.

## Core Technologies
* Python
* Pandas & NumPy
* Statsmodels (Proportion metrics)
* Seaborn & Matplotlib
