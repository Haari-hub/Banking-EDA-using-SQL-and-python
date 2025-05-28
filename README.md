# Banking-EDA-using-SQL-and-python
This project performs basic understanding of Correlation analysis & Data Analysis (EDA) on a banking dataset using Python and  SQL to uncover patterns, trends, and customer behavior insights.

 # Problem Statement

A financial institution is seeking to derive actionable insights from customer banking data to inform business strategies, credit risk modeling, and targeted marketing. The goal of this EDA is to understand the distribution and correlation of key features including income levels, credit card usage, nationality, and savings trends.

# Tools
- Python (Pandas, Matplotlib, Seaborn)
- SQL (for data extraction & filtering)
- Jupyter Notebook
- Matplotlib/Seaborn for visualization

  ## Analysis Performed

# 1. Univariate Analysis
- Distribution of Gender, Occupation, Income Band, Nationality, etc.
- Visualized using countplot().

# 2. Bivariate Analysis
- Analyzed the relationship between Income Band and Nationality.
- Used hue in Seaborn to identify patterns across categories.

# 3. Numerical Feature Distribution
- Histograms and KDE plots for:
  - Estimated Income
  - Superannuation Savings
  - Credit Card Balance
  - Bank Loans and Deposits

# 4. Correlation Heatmap
- Computed Pearson correlation between numerical features.
- Identified moderately positive correlation between income and savings.

   # Key Insights

  Income Band Distribution: The majority of customers fall into the Low and Medium income bands.
  Nationality Trends: Certain nationalities are overrepresented in specific income bands.
  Estimated Income and Credit Card Balance show a slight positive correlation.
  Superannuation Savings correlates moderately with Estimated Income (ρ ≈ 0.37).
  Some features may exhibit skewness and require transformation before modeling.
