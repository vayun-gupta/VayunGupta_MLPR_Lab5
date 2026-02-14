# MLPR Lab-5

## Repository Overview

This repository contains my completed Jupyter Notebook for MLPR Lab 5. The notebook includes:

- Implementation of K-Nearest Neighbors (KNN)
- Use of different distance metrics
- Cross-validation for model evaluation
- Bias-variance analysis
- Code outputs, visualizations, and report answers

The repository is public and contains all required code, outputs, analysis, and explanations.

## Aim of the Assignment

The aim of this lab was to understand and implement distance-based classification methods, especially the K-Nearest Neighbors (KNN) algorithm. The objective was to:

- Explore different distance metrics
- Evaluate model performance
- Understand the effect of different values of K
- Analyze bias and variance in KNN
- Use cross-validation to improve reliability

## Methodology

### 1. Data Preprocessing
- Loaded the dataset
- Checked for missing values
- Performed feature scaling where necessary
- Split data into training and testing sets

### 2. Model Implementation
- Implemented KNN classifier
- Tested multiple values of **K**
- Compared different distance metrics such as:
  - Euclidean
  - Manhattan
  - Minkowski

### 3. Model Evaluation
- Calculated accuracy scores
- Generated confusion matrix
- Used cross-validation for better performance estimation
- Compared training vs testing accuracy to study bias and variance

## Visualizations

Refer to the images folder in the repository

## Key Findings

- Smaller values of K resulted in low bias but high variance.
- Larger values of K produced smoother decision boundaries but slightly increased bias.
- Euclidean distance performed well for scaled numerical data.
- Cross-validation gave a more stable estimate of model accuracy compared to a single train-test split.
- Feature scaling significantly improved performance.

## Bias-Variance Observation

- **Low K (e.g., 1–3):**
  - Very sensitive to noise
  - High variance
  - Risk of overfitting

- **High K:**
  - More stable predictions
  - Higher bias
  - Risk of underfitting

Choosing an optimal K balances both bias and variance.

## Conclusion

This lab helped in understanding how distance-based algorithms work in practice. KNN is simple yet powerful, but its performance depends heavily on:

- Choice of distance metric
- Proper scaling of features
- Selection of K
- Use of cross-validation

Overall, the experiment demonstrated the importance of model tuning and validation to achieve reliable results.



## Author

Vayun Gupta  
U20240020
DSEB
