# Fraud Detection in E-commerce

## Project Overview

This project aims to build a machine learning-based solution to detect fraudulent transactions in an e-commerce dataset. It leverages various techniques such as data preprocessing, exploratory data analysis (EDA), feature engineering, and model building using deep learning and classical machine learning algorithms.

## Key Sections

1. **Data Preparation**: 
   - Acquisition of transaction data.
   - Handling missing values, encoding categorical features, and normalizing data for model readiness.

2. **Exploratory Data Analysis (EDA)**: 
   - Visualizing the distribution of key variables.
   - Identifying potential patterns in fraudulent and non-fraudulent transactions.

3. **Feature Engineering**: 
   - Dimensionality reduction via Principal Component Analysis (PCA) to optimize model performance.

4. **Modeling**:
   - Implemented machine learning models include Random Forest and XGBoost, along with deep learning models (CNN).
   - Model tuning through grid search and hyperparameter optimization.

5. **Evaluation**:
   - Models are evaluated using classification metrics such as accuracy, AUC, confusion matrix, and classification report.

## Requirements

- **Python 3.x**
- **Libraries**: 
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `tensorflow`
  - `torch`
  - `seaborn`
  - `matplotlib`
  - `imblearn`

## How to Run the Project

1. Clone the repository and install required packages using:

    ```bash
    pip install -r requirements.txt
    ```

2. Load the dataset using the provided Google Drive link or local directory.

3. Run the Jupyter notebook to execute each cell step by step.

## Key Models Used

- **Random Forest**
- **XGBoost**
- **Convolutional Neural Networks (CNN)**

## License

This project is licensed under the MIT License.