# Datheon Machine Learning & Data Science Internship

## Overview

This repository contains my project submissions for the **Datheon Machine Learning & Data Science Internship**.

The projects demonstrate practical applications of machine learning using Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-Learn. They cover data exploration, preprocessing, feature engineering, model training, evaluation, and visualization.

## Projects

### Task 1: Multi-Class Benchmark Classification Pipeline

**Dataset:** Iris dataset

**Objective:** Build and compare supervised classification models to predict flower species from their measurements.

#### Technologies Used

- Python
- Pandas and NumPy
- Scikit-Learn
- Matplotlib and Seaborn
- Jupyter Notebook

#### Workflow

1. Loaded and explored the Iris dataset.
2. Performed exploratory data analysis using a Seaborn pairplot.
3. Split the dataset into training and testing sets using an 80/20 ratio.
4. Standardized numerical features using `StandardScaler`.
5. Trained Logistic Regression and Decision Tree classifiers.
6. Evaluated models using accuracy, macro precision, macro recall, and macro F1-score.
7. Generated classification reports and confusion matrix heatmaps.
8. Visualized decision boundaries using two selected features.

#### Key Learning Outcomes

- Understanding supervised multi-class classification.
- Exploring datasets and identifying feature relationships.
- Applying feature scaling without data leakage.
- Training and comparing classification algorithms.
- Evaluating classification performance using multiple metrics.
- Visualizing decision boundaries and confusion matrices.

**Notebook:** `Task_1_Iris_Classification/iris_classification.ipynb`

---

### Task 2: Real Estate Housing Price Prediction — Ridge & Lasso Regression

**Dataset:** California Housing dataset

**Objective:** Predict median house values using regression algorithms and compare the performance of ordinary least squares, Ridge Regression, and Lasso Regression.

#### Technologies Used

- Python
- Pandas and NumPy
- Scikit-Learn
- Matplotlib and Seaborn
- Jupyter Notebook

#### Workflow

1. Loaded and explored the California Housing dataset.
2. Examined dataset structure, descriptive statistics, missing values, and duplicate records.
3. Visualized the target variable distribution and numerical feature correlations.
4. Split the dataset into training and testing sets.
5. Handled missing numerical and categorical values using imputation.
6. Standardized numerical features and encoded categorical attributes using one-hot encoding.
7. Engineered interaction features to explore relationships between predictors.
8. Trained an ordinary least squares Linear Regression model.
9. Used `GridSearchCV` with cross-validation to tune the regularization parameter (`alpha`) for Ridge and Lasso Regression.
10. Compared models using Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R² score.
11. Created actual-versus-predicted plots and residual analysis visualizations.
12. Examined residual distributions to understand prediction errors.

#### Key Learning Outcomes

- Understanding continuous-value regression problems.
- Performing data cleaning, imputation, and preprocessing.
- Applying categorical encoding and feature scaling.
- Engineering interaction features.
- Understanding multicollinearity and the role of regularization.
- Tuning model hyperparameters using cross-validation.
- Comparing regression models using multiple evaluation metrics.
- Interpreting prediction errors through residual analysis.

**Notebook:** `Task_2_Housing_Price_Regression/housing_price_regression.ipynb`

---

## Repository Structure

```text
Datheon_Machine_Learning_and_Data_Science_Internship/
├── README.md
├── Task_1_Iris_Classification/
│   └── iris_classification.ipynb
└── Task_2_Housing_Price_Regression/
    └── housing_price_regression.ipynb
```

## Installation and Setup

### Prerequisites

- Python 3.10 or later
- Jupyter Notebook or Visual Studio Code with the Jupyter extension
- An internet connection to download the datasets from their source URLs

### 1. Clone the Repository

```bash
git clone https://github.com/sarthak0422/Datheon_Machine_Learning_and_Data_Science_Internship.git
cd Datheon_Machine_Learning_and_Data_Science_Internship
```

### 2. Install Dependencies

```bash
python -m pip install pandas numpy matplotlib seaborn scikit-learn jupyter ipykernel
```

### 3. Open the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Alternatively, open the repository folder in Visual Studio Code and open either notebook.

### 4. Run the Notebooks

- Task 1: Open `Task_1_Iris_Classification/iris_classification.ipynb`.
- Task 2: Open `Task_2_Housing_Price_Regression/housing_price_regression.ipynb`.

Select the appropriate Python environment and execute the cells sequentially from top to bottom.

## Results and Evaluation

Each notebook contains its own evaluation results, visualizations, and observations.

- **Task 1:** Classification metrics, classification reports, confusion matrices, and decision boundary plots.
- **Task 2:** Regression metrics, cross-validation results, actual-versus-predicted plots, and residual analysis.

The notebooks report the measured results obtained during execution. Model performance should be interpreted using the recorded test-set metrics rather than assumed or prefilled values.

## General Learning Outcomes

Through these projects, I have gained practical experience with:

- Exploratory data analysis and data visualization.
- Data preprocessing and feature engineering.
- Supervised classification and regression.
- Training and comparing machine learning models.
- Model evaluation and performance interpretation.
- Cross-validation and hyperparameter tuning.
- Feature scaling, categorical encoding, and regularization.
- Visualizing model predictions and errors.

## Author

**Name:** Sarthak Suresh Tambde

**GitHub:** [sarthak0422](https://github.com/sarthak0422)

**LinkedIn:** [Sarthak Tambde](https://www.linkedin.com/in/sarthaktambde/)

---

*Additional internship tasks will be documented in their respective folders as they are completed.*
