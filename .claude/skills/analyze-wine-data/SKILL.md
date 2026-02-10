# Skill: Analyze Wine Data

## Goal
Perform exploratory data analysis (EDA) on the UCI Wine dataset to understand its structure, distributions, and relationships between features and the target variable (wine class).

## Steps
1.  **Load Data**: Load the UCI Wine dataset using `sklearn.datasets.load_wine()`.
2.  **Convert to Polars DataFrame**: Convert the loaded dataset into a Polars DataFrame for efficient data manipulation.
3.  **Basic Statistics**: Display basic statistical summaries for all features (mean, median, std, min, max, etc.).
4.  **Class Distribution**: Analyze the distribution of the target variable (wine classes).
5.  **Feature Distributions**: For each feature, visualize its distribution using histograms or box plots. Consider overlaying distributions by wine class to identify discriminative features.
6.  **Correlation Matrix**: Compute and visualize the correlation matrix between features. Pay attention to correlations with the target variable.
7.  **Pair Plots/Scatter Plots**: Select a few key features and visualize their relationships using scatter plots or pair plots, colored by wine class.
8.  **Outlier Detection**: Identify potential outliers in the dataset.
9.  **Report Findings**: Summarize key insights gained from the EDA, including potential features for modeling and any data quality issues.
