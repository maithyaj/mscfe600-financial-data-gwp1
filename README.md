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

mscfe600-financial-data-gwp1/
│
├── data/                   # Contains raw financial data
├── notebooks/              # Jupyter notebooks for analysis
│   ├── task1_data_quality.ipynb
│   ├── task2_yield_curve_modeling.ipynb
│   ├── task3_exploiting_correlation.ipynb
│   ├── task4_etf_analysis.ipynb
│
├── reports/                # Generated reports (PDF/HTML)
│   ├── task1_report.pdf
│   ├── task2_report.pdf
│
├── requirements.txt        # Python dependencies
├── .gitignore              # Git ignore file
└── README.md               # Project overview and instructions

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
