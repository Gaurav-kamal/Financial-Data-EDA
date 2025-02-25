# Financial Risk Analysis

## Overview
This project performs exploratory data analysis (EDA) on a financial risk assessment dataset. The analysis includes data preprocessing, visualization, and statistical insights to understand various risk factors and their relationships.

## Dataset
The dataset used for this analysis contains financial and demographic information, including:
- Age
- Gender
- Education Level
- Marital Status
- Income
- Credit Score
- Loan Amount
- Loan Purpose
- Employment Status
- Years at Current Job
- Payment History
- Debt-to-Income Ratio
- Assets Value
- Number of Dependents
- Previous Defaults
- Marital Status Change
- Risk Rating

## Requirements
To run this analysis, you need the following libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

You can install them using:
```bash
pip install numpy pandas matplotlib seaborn
```

## Data Preprocessing
- The dataset is loaded using Pandas.
- Missing values are handled using `dropna()`.
- Data types are inspected using `df.info()`.
- Unique values for categorical columns are analyzed.

## Exploratory Data Analysis (EDA)
Several visualizations are generated to understand the data:
1. **Distribution Plots**:
   - Age
   - Income
   - Credit Score
   - Loan Amount
   - Debt-to-Income Ratio
   - Assets Value
   - Years at Current Job
2. **Count Plots**:
   - Gender
   - Education Level
   - Marital Status
   - Loan Purpose
   - Employment Status
   - Payment History
   - Number of Dependents
   - Risk Rating
3. **Boxplots & Violin Plots**:
   - Income by Risk Rating
   - Credit Score by Education Level
   - Debt-to-Income Ratio by Employment Status
   - Assets Value by Gender
   - Income by Marital Status
4. **Scatter Plots**:
   - Age vs Income (hue = Risk Rating)
   - Credit Score vs Loan Amount (hue = Risk Rating)
5. **Heatmaps**:
   - Correlation Matrix for numerical variables
   - Correlation Matrix for categorical variables (encoded)
6. **Jointplots**:
   - Age vs Debt-to-Income Ratio
   - Income vs Credit Score

## Usage
Run the script in a Python environment:
```bash
python financial_risk_analysis.py
```
The output will include various statistical plots and insights into financial risk factors.

## Conclusion
This project provides valuable insights into financial risk assessment using EDA techniques. The analysis helps identify patterns and trends that impact financial risk rating.

## License
This project is open-source and available under the MIT License.

