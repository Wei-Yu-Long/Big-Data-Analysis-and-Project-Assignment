# Online Retail Data Analysis Project

## Overview

This project performs comprehensive analysis of online retail data to identify high-value customers and understand purchasing patterns. The analysis combines data visualization, customer segmentation, and machine learning techniques to provide actionable business insights.

## Project Structure

The project is divided into three main parts:

### Part A: Data Exploration and Visualization
- **Formulate questions**: Identify, examine, organize, cleanse, and integrate data that can help answer these questions
- **Develop a plan**: Identify potential gaps and pitfalls in the data and work to address them
- **Find the data source**: Confirm the refined question, back up the question, and source the data.

### Part B: Data Visualization and Insights
- **Bar Charts**: Shows percentage of high-value customers by country
- **Scatter Plots**: Visualizes relationship between purchase frequency and unit price
- **correlation coefficient matrix**: Examines relationships between key features
- **Time Series Analysis**: Tracks monthly high-value customer orders
- **Holiday Product Analysis**: Identifies seasonal product trends

### Part C: Machine Learning Classification
- **Feature Engineering**: Prepares data for machine learning models
- **Model Training**: Implements Logistic Regression and Random Forest classifiers
- **Hyperparameter Tuning**: Uses GridSearchCV for model optimization
- **Model Evaluation**: Compares model performance using various metrics

## Key Findings

### Customer Segmentation
- **High-Value Customers**: 2.4% of total customers identified as high-value
- **Geographic Distribution**: UK (GB) has the highest concentration of high-value customers (2.5%)
- **Price Difference**: High-value customers have 23.5% higher median unit price (£2.55 vs £1.95)

### Seasonal Patterns
- **Peak Season**: December shows highest order volume (1,850 orders)
- **Holiday Products**: Christmas-themed products account for 6.1% of total sales

### Machine Learning Results
- **Best Model**: Random Forest with optimized hyperparameters
- **Performance**: 99.8% accuracy with 95.5% F1-score for high-value customer classification
- **Feature Importance**: Purchase frequency is the most important predictor

## Data Sources

- **Primary Dataset**: Online Retail.xlsx (UCI Machine Learning Repository)
- **Dataset Size**: 397,884 transactions after cleaning
- **Time Period**: 2010-2011 retail data
- **Countries**: 37 countries represented

## Technical Implementation

### Data Processing
- **Missing Value Handling**: Removed records with missing CustomerID and Description
- **Data Filtering**: Excluded negative quantities and prices
- **Country Standardization**: Converted country names to ISO codes using pycountry

### Visualization Libraries
- **Matplotlib**: Core plotting library
- **Seaborn**: Statistical data visualization
- **Pandas**: Data manipulation and analysis

### Machine Learning
- **Scikit-learn**: Classification algorithms and model evaluation
- **Feature Engineering**: Label encoding for categorical variables
- **Model Selection**: Logistic Regression and Random Forest comparison
- **Hyperparameter Tuning**: Grid search with cross-validation

## Files Generated

1. **cleaned_retail_data.csv**: Processed retail transaction data
2. **customer_segments.csv**: Customer segmentation results with high-value labels
3. **Assignment 1.ipynb**: Complete Jupyter notebook with all analysis

## Dependencies

```python
pandas>=2.3.0
numpy>=1.26.4
matplotlib>=3.10.0
seaborn>=0.13.2
pycountry>=24.6.1
scikit-learn>=1.0.0
```

## Usage

1. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn pycountry scikit-learn
   ```

2. Ensure the Online Retail.xlsx file is in the same directory

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook "Assignment 1.ipynb"
   ```

## Business Applications

This analysis provides valuable insights for:
- **Customer Relationship Management**: Identifying and targeting high-value customers
- **Inventory Management**: Optimizing product mix based on customer segments
- **Revenue Optimization**: Focusing on customers with higher unit prices

## Methodology

The project follows a systematic approach:
1. **Data Exploration**: Understanding data structure and quality
2. **Data Cleaning**: Handling missing values and outliers
3. **Feature Engineering**: Creating meaningful customer segments
4. **Visualization**: Creating informative charts and graphs
5. **Machine Learning**: Building predictive models for customer classification
6. **Model Evaluation**: Assessing model performance and feature importance

## References

- UCI Machine Learning Repository: Online Retail Dataset
- Tableau Data Visualization Best Practices
- R for Data Science: Data Visualization Principles
- Academic papers on e-commerce customer behavior analysis

## Comprehensive Final Report 

- **url: https://cn.overleaf.com/read/qwdsgvnrkxtj#8cd214
---
