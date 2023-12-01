# A/B Testing Analysis for bombabomba.com

## Project Overview

This project involves the analysis of an A/B test conducted by bombabomba.com to compare the performance of two bidding types: "Maximum Bidding" (control group) and "Average Bidding" (test group). The ultimate success metric is the "Purchase" variable.

## Project Structure

- `ab_testing.xlsx`: Excel file containing data for the control and test groups.
- `ab_test_analysis.ipynb`: Jupyter Notebook containing the Python code for data preparation, analysis, and hypothesis testing.
- `README.md`: This file providing an overview of the project.

## Tools Used

- Python (Pandas, NumPy, Matplotlib, SciPy)
- Jupyter Notebook

## Project Tasks

### Task 1: Preparing and Analyzing Data

- Loaded and examined data for both control and test groups.
- Checked data types, summary statistics, and quantiles for key variables.

### Task 2: Defining the Hypothesis of the A/B Test

- Defined null (H0) and alternative (H1) hypotheses for the A/B test.
- Calculated and compared mean purchase values for the control and test groups.

### Task 3: Hypothesis Testing

- Checked assumptions of normality and homogeneity of variance.
- Conducted a two-sample t-test to compare purchase averages between control and test groups.
- Interpreted p-values and drew conclusions.

## How to Run the Analysis

1. Install required libraries: `pandas`, `numpy`, `matplotlib`, `scipy`.
2. Open and run the `ab_test_analysis.ipynb` Jupyter Notebook.

## Results

The statistical analysis indicates that there is no statistically significant difference between the purchase averages of the control and test groups.

