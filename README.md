# Water Potability Classification using Decision Trees and Random Forests

## Overview

This project investigates the use of supervised machine learning techniques for predicting whether water is safe for human consumption based on its physicochemical properties.

The project includes exploratory data analysis, missing value handling, feature importance analysis, hyperparameter tuning, and a performance comparison between Decision Tree and Random Forest classifiers.

## Dataset

The dataset contains **3,276 water samples** with several physicochemical measurements and a binary target variable indicating whether the water is potable.

Features include:

- pH
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic Carbon
- Trihalomethanes
- Turbidity

Target:

- **Potability**
  - 0 → Not Potable
  - 1 → Potable

Dataset source:
https://www.kaggle.com/datasets/adityakadiwal/water-potability

---

## Project Workflow

### Data Exploration

- Dataset inspection
- Descriptive statistics
- Missing value analysis
- Histograms for all numerical features
- Class distribution visualization

### Water Quality Analysis

- Analysis of pH ranges according to WHO recommendations
- Scatter plot between pH and Chloramines
- Investigation of class separability

### Data Preprocessing

- Missing value imputation using feature means
- Train/Test split (70/30)

### Decision Tree

- Baseline Decision Tree classifier
- Hyperparameter tuning
- Tree visualization
- Feature importance analysis

### Random Forest

- Hyperparameter optimization
- Performance comparison with Decision Tree
- Feature importance analysis

---

## Machine Learning Models

- Decision Tree Classifier
- Random Forest Classifier

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Evaluation Metric

The models were evaluated using:

- Accuracy Score

Additionally, classification reports were generated to compare the predictive performance of each classifier.

---

## Repository Structure

```
├── Water_Potability.ipynb
├── README.md
└── water_potability.csv
```

---

## Author

Georgia Takatzoglou

M.Sc. Data and Web Science  
Physics Graduate | Machine Learning | Data Science
