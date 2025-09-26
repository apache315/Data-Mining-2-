# Data Mining 2 - Advanced Topics and Applications Project

## Overview
Comprehensive data mining project analyzing movie datasets using advanced machine learning techniques, time series analysis, and explainable AI methods.

## Datasets
- **Tabular Dataset**: Extended IMDb dataset with ~150k movie records and 32 features
- **Time Series Dataset**: Daily box office gross income for ~1k movies from release date

## Project Structure

### Module 0: Data Understanding & Preparation
- **Tabular**: Exploratory analysis, preprocessing, feature engineering
- **Time Series**: Analysis, preprocessing, approximation techniques (SAX, PAA)

### Module 1: Advanced Data Preprocessing
- **Outlier Detection**: 3+ methods from different families, 2D/3D visualization with dimensionality reduction
- **Imbalanced Learning**: Decision Tree/KNN with undersampling/oversampling techniques

### Module 2: Advanced ML & Explainable AI
- **Classification**: Multi-class prediction (5+ classes) using:
  - Logistic Regression
  - Support Vector Machines
  - Neural Networks
  - Ensemble Methods
  - Gradient Boosting
- **Regression**: Advanced non-linear regression with multiple features
- **XAI**: Implementation of explainability methods (LIME, SHAP, etc.)

### Module 3: Time Series Analysis
- **Motifs/Discords**: Pattern discovery and anomaly detection
- **Clustering**: Multiple algorithms with appropriate distance metrics
- **Classification**: KNN (Euclidean, DTW), Shapelets, advanced methods (ROCKET, CNN, RNN)
- **Sequential Pattern Mining** (optional): Frequent pattern identification

## Key Features
- Hyperparameter tuning with justification
- Comprehensive evaluation metrics (accuracy, precision, recall, F1, ROC)
- Detailed performance analysis and insights
- Visualization using dimensionality reduction techniques
- Model explainability and interpretability

## Dataset Schema
32 features including:
- Movie metadata (title, year, runtime, genre)
- Ratings and reviews (IMDb rating, user/critic reviews)
- Production details (cast, companies, awards)
- Technical specifications (regions, sound mixes)

## Requirements
- Python with data mining libraries
- Maximum 30 pages project report
- Implementation of all required modules

## Repository Structure
```
├── notebooks/
│   ├── module0_data_preparation.ipynb
│   ├── module1_preprocessing.ipynb
│   ├── module2_advanced_ml.ipynb
│   └── module3_time_series.ipynb
├── data/
├── src/
├── results/
└── report.pdf
```

## Course Information
**Data Mining: Advanced Topics and Applications (DM2)**  
Second Semester Project covering advanced data mining techniques including imbalanced learning, dimensionality reduction, anomaly detection, ensemble methods, and time series analysis.
