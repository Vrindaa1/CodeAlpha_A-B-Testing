
A/B Testing Analysis using Python

Overview

This repository contains Python code to perform an A/B testing analysis to evaluate the impact of a change or intervention on a specific metric. The analysis includes generating simulated data for control and treatment groups, performing statistical testing (t-test), and drawing actionable insights based on the results.


Code Explanation

ab_testing_analysis.py: Python script containing code to simulate data for control and treatment groups, perform t-test, and interpret results.

Simulated Data

Control Group: Simulated data without the intervention.
Treatment Group: Simulated data with the intervention.

Results

t-statistic: Measure of difference between group means.
p-value: Probability of observing data if null hypothesis is true.

Actionable Insights

Reject the null hypothesis if p-value < 0.05, indicating a significant difference between groups.
Positive t-statistic suggests treatment group metric is higher, supporting intervention effectiveness.
