# ECS764P Applied Statistics - Coursework 2

This repository contains solutions to Coursework 2 for the ECS764P Applied Statistics course at Queen Mary University of London.

## Coursework Overview

This coursework focuses on joint distributions, (in)dependence, and linear dependence by analysing two related one-dimensional datasets $X$ and $Y$.

- **Task 1: Dataset Selection**
  - Select two one-dimensional datasets $X$ and $Y$ that you expect to exhibit an interesting dependency.
  - Briefly motivate the choice and explain why a dependency is plausible.

- **Task 2: Data Retrieval & Descriptive Statistics**
  - Retrieve both datasets programmatically (e.g., via an API) such that the notebook runs in the QMUL environment.
  - Plot the data and present basic descriptive statistics.
  - Visualise the paired data in a clear and informative 2D plot.

- **Task 3: Test for Linear Dependence**
  - Choose a significance level $\alpha$ and test whether $X$ and $Y$ are linearly dependent.
  - Plot the test statistic on its theoretical PDF and shade the critical region and the p-value.
  - State the conclusion in context.

- **Task 4: Model the Dependency**
  - **(a) If the test suggests linear dependence:**
    - Perform linear regression and plot the fitted relationship.
    - Plot a histogram of the residuals.
    - Compute the sample standard deviation of residuals $s(\varepsilon_1,\ldots,\varepsilon_n)$.
    - Using a KS-test at $\alpha = 0.05$, test whether residuals could come from a normal distribution with mean 0 and standard deviation $s(\varepsilon_1,\ldots,\varepsilon_n)$.
    - Plot the KS test statistic on the Kolmogorov distribution and shade the critical region and the p-value.
  - **(b) If the test suggests no linear dependence:**
    - Use the 2D plot to identify a plausible non-linear dependency $Y \approx f(X)$ (e.g., quadratic or exponential).
    - Fit parameters using OLS, plot the fitted curve, and plot a histogram of residuals.

- **Task 5: Test for Independence**
  - Propose a test (based on marginals and course concepts) for whether the joint distribution of $X, Y$ is a product distribution (i.e., whether $X$ and $Y$ are independent).

## Requirements

Python 3.11.14 is used for this coursework.

## Files

- `coursework-1b.ipynb`: Main Jupyter notebook containing all solutions
- `coursework-1b.pdf`: PDF export of the notebook
- `requirements.txt`: Python package dependencies

## Author

Philipp Schmidt

## Due Date

Thursday, 15. January 2026 (12:00 GMT)
