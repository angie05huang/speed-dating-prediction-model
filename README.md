# Speed Dating Match Prediction using Random Forest

This project explores whether machine learning can predict romantic matches using the Speed Dating dataset from OpenML. A Random Forest classifier was trained to analyze participant preferences, demographics, and interaction features to predict whether two individuals would result in a match.

## Project Overview

The notebook performs:
- Data loading and preprocessing
- Feature engineering and cleaning
- Correlation analysis
- Random Forest model training
- Hyperparameter tuning using GridSearchCV
- Model evaluation and feature importance analysis

The dataset was filtered to include:
- Male participants only
- Pairs that had not previously met
- Cleaned numerical and categorical features for prediction modeling :contentReference[oaicite:1]{index=1}

---

## Features

- Data cleaning and preprocessing pipeline
- Correlation heatmap visualization
- Feature selection and removal of highly correlated variables
- Random Forest classification model
- Hyperparameter tuning with GridSearchCV
- Accuracy and classification report evaluation
- Top feature importance extraction

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- Google Colab

---

## Model Results

### Best Hyperparameters
- `max_depth = 8`
- `n_estimators = 150`

### Performance
- Accuracy: **84.8%**
- Best Cross-Validation AUC-ROC Score: **0.760** :contentReference[oaicite:2]{index=2}

### Top Predictive Features
Some of the most important features included:
- `attractive_partner`
- `funny_partner`
- `guess_prob_liked`
- `interests_correlate`
- `expected_num_matches` :contentReference[oaicite:3]{index=3}

---

## Key Insights

The analysis showed that perceived attractiveness, humor, and shared interests were among the strongest predictors of a successful match. Correlation analysis also revealed that interaction-based features were significantly more predictive than demographic features alone. :contentReference[oaicite:4]{index=4}

---

## What I Learned

Through this project, I learned:
- How to preprocess and clean real-world datasets
- Feature engineering techniques for classification problems
- Random Forest model training and tuning
- Model evaluation using AUC-ROC, accuracy, and classification metrics
- How to interpret feature importance in ensemble learning models

---

## Future Improvements

- Compare Random Forest performance with XGBoost and Logistic Regression
- Handle class imbalance more effectively
- Add additional visualization dashboards
- Explore neural network approaches for prediction

---

## Dataset

Speed Dating Dataset:
https://www.openml.org/search?type=data&id=40536&sort=runs&status=active

---

## Author

Angie Huang  
UC Berkeley — Data Science & Economics
