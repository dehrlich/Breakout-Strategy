# Breakout Strategy

### Project Motivation:

- To implement and evaluate a long/short equities breakout strategy.

- The notebook covers data collection and inspection, stock universe construction, long/short signal calculation based on rolling lookback window, projected returns based on breakout strategy, and removal of outlier ticker symbols based on Kolmogorov-Smirnov (KS) Test.

### File Descriptions:


    project_2.ipynb
    | - Jupyter notebook containing all data collection, cleaning, and data frame construction, breakout strategy signal construction and implementation, projected returns, and statistical significance (KS, p-value) testing functions.
    helper.py
    |- helper file to set some configuation parameters
    project_helper.py
    |- helper file to abstract graphing functions
    project_test.py
    |- unit tests to flag any major errors
    README.md


### Installations:
- This project requires access to Quandl dataset hosted on Udacity instances for the "AI for Trading" course.
- You will need a python environment with the following:
    - pandas, numpy, scipy, plotly, os, math, requests
    - python verson 3.6 or higher

### Instructions:
1. Run each cell in 'project_2.ipynb' in sequence. Make sure the Jupyter notebook is in the same level of the directory as 'helper.py', 'project_helper.py', 'project_tests.py', and 'tests.py'.