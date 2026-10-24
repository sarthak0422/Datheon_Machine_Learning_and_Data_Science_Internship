# Datheon Machine Learning & Data Science Internship

## Overview

This repository contains my project submissions for the Datheon Machine Learning & Data Science Internship.

The projects focus on data preprocessing, machine learning model development, evaluation, and visualization using Python and Scikit-Learn.

## Task 1: Multi-Class Benchmark Classification Pipeline

**Dataset:** Iris dataset

**Objective:** Build and compare supervised classification models to predict flower species from their measurements.

### Technologies Used

- Python
- Pandas and NumPy
- Scikit-Learn
- Matplotlib and Seaborn
- Jupyter Notebook

### Workflow

1. Loaded and explored the Iris dataset.
2. Performed exploratory data analysis using a Seaborn pairplot.
3. Split the data into training and testing sets using an 80/20 ratio.
4. Standardized the features using StandardScaler.
5. Trained Logistic Regression and Decision Tree classifiers.
6. Evaluated accuracy, macro precision, macro recall, and macro F1-score.
7. Generated classification reports and confusion matrix heatmaps.
8. Visualized two-feature decision boundaries.

### Project Structure

```text
Internship/
└── Task_1_iris_classification/
    └── iris_classification.ipynb
```

### How to Run

1. Clone or download this repository.
2. Install the required libraries:

   `pip install pandas numpy matplotlib seaborn scikit-learn jupyter ipykernel`

3. Open `iris_classification.ipynb` in Jupyter Notebook or VS Code.
4. Run the notebook cells from top to bottom.

The notebook loads the Iris dataset from the supplied CSV URL, so an internet connection is required unless a local CSV copy is used.

### Results

The notebook contains the actual benchmark metrics, classification reports, confusion matrix heatmaps, and decision boundary visualizations.

Model performance should be interpreted using the recorded test-set results.

## Learning Outcomes

- Understanding supervised multi-class classification
- Data exploration and preprocessing
- Avoiding data leakage during feature scaling
- Training and comparing classification algorithms
- Evaluating models with multiple classification metrics
- Visualizing classification performance

## Author

**Name:** Sarthak Suresh Tambde

**GitHub:** https://github.com/sarthak0422

**Linkedin:** https://www.linkedin.com/in/sarthaktambde/

---

Additional internship tasks will be documented in their respective folders as they are completed.
