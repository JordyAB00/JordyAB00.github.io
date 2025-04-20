# Credit Risk Classification

## Overview
This project develops a machine learning approach to predict loan default risk, enabling financial institutions to make more informed lending decisions. Using a dataset of 10,000 loan applications with demographic, financial, and loan attributes, I build and compare multiple classification models to identify the most effective predictive approach.

## Key Features
- Comprehensive data cleaning and feature engineering pipeline
- Comparative analysis of Random Forest, Neural Network, and Naive Bayes models
- Business impact analysis with profit optimization
- Risk segmentation and strategic recommendations

## Technical Highlights
- **Best Model**: Random Forest with 93.3% accuracy and 0.931 AUC
- **Feature Engineering**: Created interaction features that significantly improved model performance
- **Risk Bucketing**: Developed a 6-tier risk classification system with validation
- **Business Optimization**: Identified profit-maximizing decision threshold at 0.30

## Technologies Used
- R (tidyverse, caret, randomForest, neuralnet, e1071)
- Machine Learning (supervised classification)
- Data Visualization (ggplot2, corrplot, gridExtra)
- Financial Analysis (risk-based pricing, ROI calculation)

## Results
The implemented model can increase profitability by approximately $1.5 million by selectively approving 77.9% of loan applications while reducing the default rate to 5.7% (from a baseline of 22.1%). The analysis provides actionable insights for different customer segments and risk tiers.

## Repository Structure
- `credit_risk_analysis.Rmd`: R Markdown file with full analysis
- `credit_risk_analysis.html`: Rendered HTML report with interactive elements
- `/data`: Dataset used for analysis
- `/images`: Visualizations and figures

## How to Run
1. Clone this repository
2. Open the .Rmd file in RStudio
3. Install required packages listed in the setup chunk
4. Run all chunks to reproduce the analysis
