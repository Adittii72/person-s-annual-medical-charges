# Linear Regression Practice Project

> ⚠️ **This is a PRACTICE PROJECT** - Not a real-world application. This repository serves as a learning resource for understanding Linear Regression concepts and machine learning fundamentals.

## Project Overview

This project works with the medical charges dataset to predict annual medical charges based on various patient attributes. The main focus is on learning linear regression techniques step-by-step, from basic concepts to using machine learning libraries.

## Dataset

- **Source**: Medical charges dataset
- **File**: `medical.csv`
- **Attributes**:
  - Age
  - BMI (Body Mass Index)
  - Number of Children
  - Smoker Status
  - Sex
  - Region
  - Charges (Target Variable)

## Topics & Concepts Practiced

### 1. **Data Loading & Exploration**
- Loading CSV files using Pandas
- Exploring dataset structure with `.info()` and `.describe()`
- Viewing raw data

### 2. **Data Visualization**
- Histograms with marginal distributions (using Plotly)
- Scatter plots for relationships
- Categorical vs. numerical visualizations
- Data distribution analysis

### 3. **Statistical Analysis**
- Computing descriptive statistics
- Correlation analysis between variables
- Correlation matrices
- Heatmaps for visualizing correlations

### 4. **Data Preprocessing**
- Filtering datasets (e.g., non-smokers only)
- Data type conversions
- Mapping categorical values to numeric values

### 5. **Linear Regression Fundamentals**
- Understanding the linear equation: `y = mx + b` (or `y = wa * x + b`)
- Creating custom linear regression functions
- Manual parameter optimization
- Visualizing fit lines against actual data

### 6. **Model Evaluation**
- Root Mean Squared Error (RMSE) calculation
- Understanding loss/error metrics
- Parameter tuning based on error rates

### 7. **Scikit-Learn Implementation**
- Using `LinearRegression` from scikit-learn
- Fitting models to data
- Making predictions with trained models
- Understanding model attributes (`coef_`, `intercept_`)

### 8. **Libraries & Tools Used**
- **Pandas**: Data manipulation and loading
- **NumPy**: Numerical computations
- **Matplotlib**: Static visualizations
- **Seaborn**: Statistical visualizations
- **Plotly**: Interactive visualizations
- **Scikit-learn**: Machine learning models

## Files in This Repository

```
├── linear_regression.ipynb              # Main Jupyter notebook with all code and analysis
├── medical.csv              # Dataset file
├── anaconda_projects/       # Anaconda project configuration
└── README.md                # This file
```

## How to Use

1. **Open the notebook**: `linear_regression.ipynb`
2. **Install required packages** (if not already installed):
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter
   ```
3. **Run the cells** sequentially to understand each concept
4. **Experiment**: Try modifying parameters and see how results change

## Key Learnings

- Linear regression is a fundamental ML algorithm for predicting continuous values
- Manual parameter tuning helps understand how models work before using libraries
- Visualization is crucial for understanding data relationships
- Model evaluation metrics like RMSE help determine model performance
- Scikit-learn simplifies the implementation of complex algorithms

## Disclaimer

This project is created for **educational purposes only**. The predictions and models here are meant to demonstrate concepts, not for real-world medical decision-making.

---

**Created**: April 2026  
**Status**: Practice/Learning Project
