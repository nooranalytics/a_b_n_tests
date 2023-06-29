# A/B/N Testing for Checkout Page Optimization

Welcome to this project! This repository holds an exploratory data analysis that involves A/B/N testing. The aim is to assess the performance of three different versions (A, B, and C) of a checkout page to determine which leads to more purchases.

## Introduction

A/B/N testing is a user experience research methodology that consists of a randomized experiment with two or more variants. In this project, we aim to identify which variant of the checkout page (A, B, or C) can drive more purchases, ultimately leading to enhanced business outcomes.

## Getting Started

The code for this project is written in Python.

## Required Packages

To run the code in this project, you will need to install the following Python packages:

```python
pip install pandas numpy seaborn scipy matplotlib statsmodels pingouin
```

## Dataset

The data used for this project has the following structure:

| Unnamed: 0 | user_id | checkout_page | order_value | purchased | gender | browser | time_on_page |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 0 | 877621 | A | 29.41 | 1 | F | chrome | 66.17 |
| 1 | 876599 | A | null | 0 | M | firefox | 49.80 |
| 2 | 905407 | A | 27.45 | 1 | M | chrome | 56.74 |
| 3 | 883562 | A | 30.60 | 1 | M | safari | 71.89 |
| 4 | 840542 | A | 29.67 | 1 | F | safari | 67.41 |

## Steps in A/B/N Testing

1. Descriptive statistics.
2. Null values handling.
3. Checking if duplicates are acceptable or not based on business logic.
4. Checking data types.
5. Identifying unique users.
6. Evaluating data distribution.
7. Correlations for categorical and numerical variables.
8. Basic metrics, like conversion rates across the A/B/N versions.
9. Plotting a distribution plot, or a KDE plot of the different versions.
10. Basic metrics like purchases count, average, and page views.
11. Calculating the z-test delta to examine whether users have been fairly assigned.
12. Calculating the effect size.
13. Calculating sample size.
14. Deciding on purchased and checkout page variables and running tests on that with proportion z-test.
15. Calculating confidence intervals for each A/B, B/C, A/C combination.
16. Comparing all at once, with a pairwise_test.
17. Additional attribute exploration, like checkout_page and time_on_page, and running a t-test.
