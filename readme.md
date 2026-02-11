# Telco Customer Churn Analysis

**Project**
- **Description:** Predict customer churn for a telecom provider using exploratory data analysis, feature engineering, and supervised learning models. The repository contains the dataset and the main analysis notebook used for modeling and evaluation.

**Dataset**
- **File:** [Telco-Customer-Churn.csv](Telco-Customer-Churn.csv)
- **Notes:** Original dataset contains customer demographics, account information, services, and churn labels.

**Notebook**
- **Primary analysis:** [trio_model.ipynb](trio_model.ipynb)
- **Contents:** data loading, cleaning, EDA, preprocessing, model training, evaluation, and simple model interpretation.

**Getting Started**
- **Python:** 3.8+
- **Quick setup:** create and activate a virtual environment, then install dependencies.

```bash
python -m venv venv
venv\Scripts\activate
pip install --upgrade pip
pip install pandas numpy scikit-learn matplotlib seaborn xgboost imbalanced-learn jupyter
```

- **Open the notebook:**

```bash
jupyter notebook trio_model.ipynb
```

**Repository Structure**
- **Telco-Customer-Churn.csv:** Dataset used for analysis.
- **trio_model.ipynb:** Jupyter notebook with the full analysis and modeling pipeline.
- **readme.md:** This file.

**What the analysis includes**
- **EDA:** distributions, correlations, and churn drivers.
- **Preprocessing:** handling missing values, encoding categorical features, scaling.
- **Modeling:** baseline classifiers, hyperparameter tuning, and an example tree-based model.
- **Evaluation:** accuracy, precision, recall, F1, ROC/AUC, and confusion matrices.

**How to Reproduce**
- Follow setup steps above.
- Open and run the cells in `trio_model.ipynb` in order.

**Results & Notes**
- The notebook demonstrates a reproducible workflow for churn prediction and includes visualizations and performance metrics. Use cross-validation and careful metric choice when comparing models on imbalanced data.

**Contact**
- **Author:** Repository owner
- **Questions / Changes:** Open an issue or contact the author directly.

**License**
- No license specified. Contact the author for reuse permissions.
