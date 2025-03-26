# Gradient Boosting Classifier with XGBoost - Breast Cancer Dataset

This repository contains a complete tutorial on using XGBoost (Extreme Gradient Boosting) to build a classification model that predicts whether a tumor is malignant or benign using the Breast Cancer Wisconsin dataset.

## Contents

- gradient_boosting_breast_cancer_tutorial.ipynb : Jupyter notebook with full code and explanations
- README.md : Project overview and usage instructions
- requirements.txt : List of required Python packages
- LICENSE : MIT license
- tutorial.docx or tutorial.pdf : Final report for submission

## Dataset

The Breast Cancer Wisconsin dataset is a binary classification dataset included in scikit-learn. It consists of 569 samples with 30 features each, used to predict whether a tumor is malignant (1) or benign (0).

## How to Run

1. Clone this repository:
```
git clone https://github.com/your-username/gradient-boosting-tutorial.git
cd gradient-boosting-tutorial
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Open the notebook:
```
jupyter notebook gradient_boosting_breast_cancer_tutorial.ipynb
```

## Learning Objectives

- Understand the concept of gradient boosting
- Train an XGBoost classifier on a real-world dataset
- Evaluate the model with confusion matrix, ROC AUC, and classification report
- Perform hyperparameter tuning using GridSearchCV
- Visualize feature importance

## License

This project is licensed under the MIT License.

## Acknowledgements

- The dataset is sourced from scikit-learn’s built-in datasets
- XGBoost library by Tianqi Chen and Carlos Guestrin
