# Workflow: Run Wine EDA

## Goal
Perform exploratory data analysis on the UCI Wine dataset, adhering to data quality rules, and generate visualizations to understand data characteristics.

## Steps
1.  **Load Dataset**: Load the UCI Wine dataset using `sklearn.datasets.load_wine()`.
2.  **Initial Data Inspection**: Convert the dataset to a Polars DataFrame. Display the first few rows, data types, and check for basic statistical summaries.
3.  **Apply Data Quality Rules**: Review and apply rules from `data-quality.md` (e.g., check for missing values, outliers, data types). Document any findings and actions taken.
4.  **Class Distribution Analysis**: Plot the distribution of the target variable (wine classes) using a bar chart.
5.  **Feature Distribution Analysis**: For each numerical feature, create histograms or box plots. Overlay these distributions by wine class to visualize how features vary across classes.
6.  **Correlation Analysis**: Compute and visualize the correlation matrix of all features. Identify highly correlated features and their relationships with the target.
7.  **Pairwise Feature Relationships**: Select a subset of important features and create scatter plots (colored by class) to observe pairwise relationships.
8.  **Summary Report**: Generate a markdown report summarizing the key insights from the EDA, including data quality findings, feature observations, and initial hypotheses for modeling.
