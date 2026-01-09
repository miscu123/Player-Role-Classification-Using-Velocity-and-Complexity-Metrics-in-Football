# Player Role Classification Using Velocity and Complexity Metrics in Football

## Project Overview

This project applies machine learning techniques to distinguish between attacking players (Forwards, FW) and defensive players (Defensive Midfielders, DM) using GPS-derived movement data. The study focuses on identifying which movement features—based on velocity characteristics and nonlinear complexity measures—are most effective in separating these two tactical roles.

Understanding these differences supports data-driven decision-making in football performance analysis, coaching, and sports science.

## Objective

The main objective of this project is to determine the most significant movement features that differentiate attacking and defensive football players by analyzing:

- Velocity-based parameters  
- Nonlinear and complexity-based movement measures  

## Data Processing

### Original Dataset

- GPS tracking data collected from football players  
- Includes multiple player roles and movement-related variables  

### Filtered Dataset

The dataset was reduced to include only two roles:

- Forwards (FW) – Attacking players  
- Defensive Midfielders (DM) – Defensive-oriented players  

## Feature Preparation

- Selection of velocity and movement complexity features  
- Data cleaning and preprocessing  
- Feature scaling and preparation for machine learning models  

## Features Used

### Velocity Parameters

- Mean Velocity  
- Coefficient of Variation (CV) of Velocity  
- Maximum Velocity  

### Complexity Measures

- Sample Entropy  
- Hurst Exponent  
- Fractal Dimension (Frac_Max)  

These features capture both physical intensity and movement irregularity, reflecting differences in tactical demands between attacking and defensive roles.

## Machine Learning Methods

The following machine learning models were implemented and compared:

- Logistic Regression  
- Random Forest Classifier (RFC)  
- Support Vector Machine (SVM)  

### Model Evaluation

- Cross-validation used for performance assessment  
- Feature importance analysis performed to identify the most discriminative variables  

## Feature Selection & Analysis

- Feature significance extracted from each machine learning model  
- Histograms used to visualize feature distributions  
- Most relevant features selected for final model evaluation  

## Results

- Machine learning models successfully distinguished between FW and DM roles  
- Both velocity-based and complexity-based features contributed to classification  
- Complexity measures (e.g., Sample Entropy and Hurst Exponent) provided additional discriminatory power beyond traditional speed metrics  

## Applications

- Football performance analysis  
- Player role classification  
- Sports science research  
- GPS-based movement analytics  
- Data-driven coaching and tactical support  

## Keywords

Football Analytics, GPS Data, Machine Learning, Movement Complexity, Player Role Classification, Sports Science
