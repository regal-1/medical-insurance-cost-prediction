
# Report

This folder contains the final written report for the **Medical Insurance Cost Prediction** project.

## Contents

- **insurance_cost_report.pdf**  
  Comprehensive analysis of factors influencing medical insurance costs, including statistical modeling, diagnostics, and machine learning results.

## Overview

The report investigates how demographic and lifestyle variables impact individual medical insurance charges. Key variables include age, BMI, smoking status, number of children, sex, and geographic region.

## Key Findings

- Smoking is the strongest predictor of insurance costs  
- BMI and age have significant positive effects on charges  
- Interaction effects (BMI × smoking) substantially improve model performance  
- Random Forest achieves the highest predictive accuracy but is less interpretable  

## Methods Covered

- Exploratory Data Analysis (EDA)  
- Multiple Linear Regression (OLS)  
- Interaction Models  
- Model Diagnostics (heteroskedasticity, normality tests)  
- Bootstrap estimation for robust inference  
- Random Forest modeling for nonlinear relationships  

## Results Summary

- Baseline regression: R² ≈ 0.75  
- Interaction model: R² ≈ 0.84  
- Random Forest: R² ≈ 0.92  

## Notes

- This report summarizes the full analytical workflow and results  
- For code and implementation details, refer to the `/notebooks` directory  
- Dataset and preprocessing steps are documented within the notebooks  

## Usage

Download the PDF to view the full report if it does not render properly in GitHub preview.
