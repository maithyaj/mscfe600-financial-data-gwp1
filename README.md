# MScFE 600 Financial Data - Group Work Project #1

## Overview
This repository contains the code, analysis, and reports for **MScFE 600 Financial Data Group Work Project #1**. The project focuses on the application of financial data analysis techniques, including tasks related to data quality assessment, yield curve modeling, correlation analysis, and empirical analysis of ETFs.

## Tasks
The project is divided into four key tasks:

1. **Data Quality**
   - Analyze and provide examples of both structured and unstructured poor-quality financial data.
   - Evaluate how to recognize poor-quality data and its impact on financial analysis.

2. **Yield Curve Modeling**
   - Fit **Nelson-Siegel** and **Cubic-Spline** models to government securities' yield data.
   - Compare the models in terms of fit and interpretation.

3. **Exploiting Correlation**
   - Use Principal Component Analysis (PCA) on simulated and real data to analyze correlations in financial variables.
   - Create scree plots to visualize variance explained by principal components.

4. **Empirical Analysis of ETFs**
   - Analyze the 30 largest holdings of a selected sector ETF.
   - Compute daily returns, covariance, and use PCA and Singular Value Decomposition (SVD) for further analysis.

## Repository Structure
- **`data/`**: This folder will contain the raw financial data used for analysis.
- **`notebooks/`**: This folder includes Jupyter notebooks for each task. Each notebook is dedicated to a specific task.
  - `task1_data_quality.ipynb`: Analysis of data quality.
  - `task2_yield_curve_modeling.ipynb`: Yield curve modeling (including Nelson-Siegel and Cubic-Spline models).
  - `task3_exploiting_correlation.ipynb`: Analysis of correlation using PCA and other methods.
  - `task4_etf_analysis.ipynb`: Empirical analysis of ETFs.
- **`reports/`**: Folder for generated reports. These reports should summarize the work done in each task.
  - `task1_report.pdf`: PDF report for Task 1.
  - `task2_report.pdf`: PDF report for Task 2.
- **`requirements.txt`**: A file that lists all the necessary Python libraries needed to run the project (e.g., `pandas`, `scikit-learn`).
- **`.gitignore`**: A file that tells Git which files and directories to ignore (e.g., virtual environments, data files, etc.).
- **`README.md`**: This file, which provides an overview of the project, setup instructions, and repository structure.

## Setup Instructions
To ensure smooth collaboration on this project, please follow the steps below:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/maithyaj/mscfe600-financial-data-gwp1.git
   cd mscfe600-financial-data-gwp1

2. **Install Dependencies** 
   Install the required Python libraries using requirements.txt:
   ```python
   pip install -r requirements.txt

3. **Run Jupyter Notebooks**
   Launch Jupyter to access the analysis notebooks
