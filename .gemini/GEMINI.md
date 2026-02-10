# Google Antigravity Project Guidelines for Wine Classification

## Project Objective
Develop a robust machine learning pipeline for classifying wines into three distinct classes using the UCI Wine dataset. The pipeline should adhere to high standards of data quality, model performance, and code maintainability.

## General Rules
- **Code Style**: All Python code must conform to PEP 8. Use `ruff` for linting and formatting.
- **Documentation**: All functions and classes must have clear docstrings. Complex logic should be explained with comments.
- **Modularity**: Break down the pipeline into well-defined, reusable modules (e.g., data loading, EDA, feature engineering, model training, evaluation).
- **Dependencies**: Explicitly list all dependencies in `pyproject.toml`.

## Dataset Specific Instructions (UCI Wine Dataset)
- **Classes**: The target variable has 3 classes. Ensure all classification metrics are appropriate for multi-class classification.
- **Data Splitting**: Always use stratified sampling when splitting data to preserve class distribution.
- **Feature Scaling**: Apply appropriate scaling to numerical features before model training.

## Model Training and Evaluation
- **Model Choice**: Use XGBoost for the classification task.
- **Cross-Validation**: Implement k-fold cross-validation for robust model training and hyperparameter tuning.
- **Evaluation Metrics**: Focus on accuracy, precision, recall, F1-score, and confusion matrix. Report both macro and weighted averages for multi-class metrics.
