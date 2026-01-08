# Codveda Technologies Internship - Machine Learning Tasks

## Overview
This repository contains the completed tasks for the Codveda Technologies Internship program. The internship focuses on building and evaluating machine learning models across different levels of complexity: Basic, Intermediate, and Advanced. I have implemented three key tasks demonstrating fundamental to advanced machine learning techniques using Python, scikit-learn, and related libraries.

## Completed Tasks

### Level 1 (Basic) - Task 2: Build a Simple Linear Regression Model
- **Objective**: Predict house prices using linear regression on the Boston Housing dataset.
- **Key Features**: Data preprocessing, model training, evaluation with R-squared and MSE, cross-validation, and visualization.
- **Dataset**: Boston Housing dataset (house Prediction Data Set.csv).
- **Results**: R-squared ~0.67, MSE ~24.3.
- **Files**: `Linear_Regression_Model.py`, `models/`, `output/`.

### Level 2 (Intermediate) - Task 1: Logistic Regression for Binary Classification
- **Objective**: Predict customer churn using logistic regression on telecom data.
- **Key Features**: Binary classification, model interpretation, ROC curve analysis, and evaluation metrics.
- **Dataset**: Churn prediction dataset (churn-bigml-80.csv for training, churn-bigml-20.csv for testing).
- **Results**: High accuracy with detailed metrics and visualizations.
- **Files**: `Logistic_Regression_Churn.py`, `Logistic_Regression_for_Binary_Classification.py`, `models/`, `output/`.

### Level 3 (Advanced) - Task 1: Build a Random Forest Classifier
- **Objective**: Classify iris species using a Random Forest model with hyperparameter tuning.
- **Key Features**: Ensemble learning, feature importance analysis, cross-validation, and performance evaluation.
- **Dataset**: Iris dataset (iris.csv).
- **Results**: Strong classification performance with feature insights.
- **Files**: `Random_Forest_Classifier.py`, `models/`, `output/`.

## Project Structure
```
Codveda Technologies Internship/
├── Data Set For Task/          # Datasets used across tasks
├── Level 1 (Basic) - Task 2 Build a Simple Linear Regression Model/
│   ├── Linear_Regression_Model.py
│   ├── README.md
│   ├── models/
│   └── output/
├── Level 2 (Intermediate) - Task 1 Logistic Regression for Binary Classification/
│   ├── Logistic_Regression_Churn.py
│   ├── Logistic_Regression_for_Binary_Classification.py
│   ├── README.md
│   ├── models/
│   └── output/
├── Level 3 (Advanced) - Task 1 Build a Random Forest Classifier/
│   ├── Random_Forest_Classifier.py
│   ├── README.md
│   ├── models/
│   └── output/
├── requirements.txt            # Python dependencies
└── task_requirements.md        # Full task descriptions
```

## Installation and Setup
1. **Clone the Repository**:
   ```
   git clone https://github.com/KhayaBotha20/Codveda-Internship.git
   cd Codveda-Internship
   ```

2. **Set Up Virtual Environment** (Recommended):
   ```
   python -m venv .venv
   # Activate: .\.venv\Scripts\Activate.ps1 (Windows PowerShell)
   ```

3. **Install Dependencies**:
   ```
   pip install -r requirements.txt
   ```

## How to Run the Tasks
Each task folder contains a dedicated script and README with detailed instructions. Ensure the virtual environment is activated before running.

- **Linear Regression**: Run `python "Level 1 (Basic) - Task 2 Build a Simple Linear Regression Model/Linear_Regression_Model.py"`
- **Logistic Regression**: Run `python "Level 2 (Intermediate) - Task 1 Logistic Regression for Binary Classification/Logistic_Regression_for_Binary_Classification.py"`
- **Random Forest**: Run `python "Level 3 (Advanced) - Task 1 Build a Random Forest Classifier/Random_Forest_Classifier.py"`

## Datasets
- **Iris Dataset**: For Random Forest classification.
- **Boston Housing Dataset**: For Linear Regression prediction.
- **Churn Dataset**: For Logistic Regression binary classification.
- All datasets are included in the `Data Set For Task/` folder.

## Outputs and Models
- **Models**: Serialized models (`.pkl` files) saved in each task's `models/` folder.
- **Visualizations**: Plots and charts saved in `output/` folders (e.g., ROC curves, confusion matrices, feature importance).
- **Metrics**: Console outputs with evaluation scores and interpretations.

## Tools and Libraries
- **Programming Language**: Python 3.x
- **Libraries**: pandas, scikit-learn, matplotlib, numpy, seaborn
- **Environment**: Jupyter Notebook compatible, but scripts run standalone

## Learning Outcomes
Through this internship, I gained hands-on experience in:
- Data preprocessing and feature engineering
- Implementing and evaluating regression and classification models
- Hyperparameter tuning and cross-validation
- Model interpretation and visualization
- Best practices in machine learning project structure

## Contact
- **Name**: Khaya Botha
- **Email**: khaya2216botha@gmail.com
- **GitHub**: KhayaBotha20

---

*This project demonstrates practical applications of machine learning algorithms for predictive modeling and classification tasks.*