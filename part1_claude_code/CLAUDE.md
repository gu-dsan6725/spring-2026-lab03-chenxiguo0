# Wine Classification Project Guidelines

## Project Objective
The primary objective of this project is to build a robust machine learning pipeline for classifying wines into three distinct classes using the UCI Wine dataset. The pipeline should demonstrate best practices in data analysis, feature engineering, model training, and evaluation.

## Coding Standards
- Adhere to PEP 8 for Python code style.
- Use clear, descriptive variable and function names.
- Include comprehensive comments for complex logic.
- Ensure all functions have docstrings explaining their purpose, arguments, and return values.

## Dataset Specific Instructions (UCI Wine Dataset)
- **Classes**: The dataset contains 3 distinct wine classes. The model should accurately predict these three classes.
- **Classification Metrics**: Focus on classification-specific metrics for model evaluation, such as accuracy, precision, recall, F1-score, and a confusion matrix.
- **Stratified Splits**: When splitting data into training and testing sets, ensure stratified sampling to maintain the original class distribution in both subsets.
- **Data Loading**: Use `sklearn.datasets.load_wine()` to load the dataset.

## ML Pipeline Components
1.  **Exploratory Data Analysis (EDA)**:
    - Utilize `polars` for efficient data manipulation and analysis.
    - Visualize data distributions, correlations, and relationships using `matplotlib`.
    - Identify potential outliers, missing values, and data inconsistencies.
2.  **Feature Engineering and Data Preparation**:
    - Handle any missing values appropriately (if any).
    - Scale numerical features as necessary for the XGBoost model.
    - Prepare data in a format suitable for model training.
3.  **XGBoost Classification Model Training**:
    - Implement an XGBoost classifier.
    - Employ cross-validation for robust model training and hyperparameter tuning.
    - Document the chosen hyperparameters and their rationale.
4.  **Model Evaluation and Reporting**:
    - Generate a comprehensive performance report including all relevant classification metrics.
    - Visualize the confusion matrix.
    - Discuss model strengths and weaknesses.
