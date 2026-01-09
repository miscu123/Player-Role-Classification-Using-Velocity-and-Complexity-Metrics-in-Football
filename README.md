# Player-Role-Classification-Using-Velocity-and-Complexity-Metrics-in-Football

Project Overview

This project applies machine learning techniques to distinguish between attacking players (Forwards, FW) and defensive players (Defensive Midfielders, DM) using GPS-derived movement data. The focus is on identifying which features are most effective in separating these two roles based on velocity characteristics and movement complexity measures.

Objective

To determine the most significant features that differentiate attacking and defensive football players by analyzing:

Velocity-based parameters

Nonlinear and complexity-based movement measures

Data Processing

Original Dataset

GPS tracking data containing multiple player roles and movement variables.

Filtered Dataset

Reduced to include only:

Attacking players (FW)

Defensive midfielders (DM)

Feature Preparation

Selected velocity and complexity features

Data prepared for machine learning models

Features Used
Velocity Parameters

Mean Velocity

Coefficient of Variation (CV) of Velocity

Maximum Velocity

Complexity Measures

Sample Entropy

Hurst Exponent

Fractal Dimension (Frac_Max)

These features aim to capture both physical intensity and movement irregularity, reflecting tactical role differences.

Machine Learning Methods

The following models were implemented and compared:

Logistic Regression

Random Forest Classifier (RFC)

Support Vector Machine (SVM)

Each model was evaluated using cross-validation, and feature importance was analyzed to identify the most discriminative variables.

Feature Selection & Analysis

Feature significance was extracted from ML models

Histograms were used to visualize the distribution of all features

The most relevant features were selected for final model evaluation

Results

Machine learning models demonstrated that both velocity-based and complexity-based features contribute to distinguishing FW and DM roles.

Complex measures (e.g., Sample Entropy and Hurst Exponent) provided additional discriminatory power beyond traditional speed metrics.

Applications

Football performance analysis

Player role classification

Sports science and GPS analytics

Data-driven coaching support
