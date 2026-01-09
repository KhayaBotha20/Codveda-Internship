# Supervised Learning Task (Beginner Level)

## Objective
Demonstrate proficiency in supervised machine learning by implementing classification and regression tasks using labeled datasets.

## Key Tasks
1. **Iris Classification with KNN**:
   - Dataset: iris.csv
   - Goal: Classify iris flowers into species (setosa, versicolor, virginica) using K-Nearest Neighbors.
   - Steps:
     - Load and explore the data.
     - Preprocess (handle missing values, normalize if needed).
     - Split into train/test sets.
     - Train KNN model, tune k parameter.
     - Evaluate with accuracy, confusion matrix, classification report.
     - Visualize results (e.g., decision boundaries).

2. **House Price Regression**:
   - Dataset: house Prediction Data Set.csv
   - Goal: Predict house prices using regression models.
   - Steps:
     - Load and clean data.
     - Feature engineering (select relevant features).
     - Train models like Linear Regression or Random Forest.
     - Evaluate with MSE, MAE, R².
     - Plot predictions vs. actuals.

3. **Customer Churn Prediction**:
   - Datasets: churn-bigml-20.csv, churn-bigml-80.csv
   - Goal: Predict if a customer will churn (binary classification).
   - Steps:
     - Combine datasets if needed.
     - Handle categorical features (encoding).
     - Address class imbalance.
     - Train classifiers (e.g., Logistic Regression, SVM).
     - Evaluate with precision, recall, AUC-ROC.
     - Feature importance analysis.

## Datasets Location
Datasets are in `../Data Set For Tasks/Data Set For Task/`.

## Tools and Libraries
- Scikit-learn for models
- Pandas/NumPy for data handling
- Matplotlib/Seaborn for visualization
- Jupyter for notebooks

## Deliverables
- Python scripts or notebooks for each task.
- Visualizations and evaluation metrics.
- Brief report on findings and model performance.