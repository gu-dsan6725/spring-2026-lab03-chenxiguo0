# Command: /plan-wine

## Goal
Generate an implementation plan for building a complete machine learning pipeline for Wine classification using the UCI Wine dataset.

## Plan Template

### 1. Objectives
- Clearly define the goals of the Wine classification pipeline.
- Specify performance metrics to optimize.

### 2. Architecture Overview
- Outline the main components of the ML pipeline (EDA, Feature Engineering, Model Training, Evaluation).
- Briefly describe the tools and libraries to be used (e.g., `polars`, `matplotlib`, `sklearn`, `xgboost`).

### 3. File Structure
- Propose a logical file and directory structure for the project.
  - `src/`: for source code files (e.g., `data_loader.py`, `eda.py`, `feature_engineering.py`, `model_trainer.py`, `evaluator.py`, `main.py`)
  - `notebooks/`: for exploratory jupyter notebooks (optional)
  - `output/`: for model artifacts, plots, and reports
  - `tests/`: for unit and integration tests

### 4. Implementation Steps

#### Step 4.1: Data Loading and Initial Exploration
- Load the UCI Wine dataset.
- Perform initial data inspection (shape, data types, missing values).

#### Step 4.2: Exploratory Data Analysis (EDA)
- Detail the specific EDA tasks to be performed, referencing the `analyze-wine-data` skill.
- Outline visualizations to generate.

#### Step 4.3: Feature Engineering and Data Preprocessing
- Describe steps for handling categorical/numerical features.
- Specify scaling or normalization techniques.
- Outline data splitting strategy (stratified train-test split).

#### Step 4.4: Model Training
- Detail the XGBoost model setup.
- Describe cross-validation strategy and hyperparameter tuning approach.

#### Step 4.5: Model Evaluation
- Detail the evaluation metrics, referencing the `evaluate-classifier` skill.
- Outline the creation of performance reports and visualizations.

#### Step 4.6: Reporting and Documentation
- Describe the final report generation.

