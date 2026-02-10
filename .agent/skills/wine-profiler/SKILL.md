# Skill: Wine Profiler

## Goal
Profile the UCI Wine dataset, including class-specific statistics, feature distributions per class, and discriminative feature analysis, to provide a deep understanding of the data for the classification task.

## Steps
1.  **Load and Prepare Data**: Load the UCI Wine dataset. Convert it to a Polars DataFrame. Ensure the target variable (wine class) is clearly defined.
2.  **Overall Data Summary**: Display general statistics for the entire dataset (mean, std, min, max, unique values, etc.).
3.  **Class-Specific Statistics**: For each wine class, calculate and display descriptive statistics for all features. This will highlight how feature values differ across classes.
4.  **Feature Distributions per Class**: For each numerical feature, generate overlaid histograms or density plots, with different colors for each wine class. This visually demonstrates the distribution of each feature within each class.
5.  **Discriminative Feature Analysis**: Identify features that show significant differences across wine classes. This can be done by:
    - **Statistical Tests**: Perform ANOVA or Kruskal-Wallis tests (depending on data distribution) to compare feature means/medians across classes.
    - **Visual Inspection**: Rely on the overlaid distribution plots to spot clear separation.
6.  **Box Plots by Class**: For key discriminative features, create box plots grouped by wine class to visualize the spread and central tendency of the feature within each class.
7.  **Correlation with Class**: Calculate point-biserial correlation or other appropriate measures to quantify the relationship between each feature and the (binary transformed) class labels, or use ANOVA F-values.
8.  **Report Findings**: Summarize the findings, identifying the most discriminative features and insights into the data structure that will be valuable for model building.
