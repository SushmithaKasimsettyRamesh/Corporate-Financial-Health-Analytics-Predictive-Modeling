# Corporate-Financial-Health-Analytics-Predictive-Modeling


## Project Overview
A comprehensive financial data analysis project that evaluates company financial health through statistical modeling, hypothesis testing, and trend analysis. This project demonstrates end-to-end data analysis workflow from data cleaning to actionable business insights.

## Objectives
- Assess company financial health using descriptive and inferential statistics
- Identify trends and patterns in revenue, expenses, and profitability
- Perform hypothesis testing to validate business performance against benchmarks
- Calculate key financial ratios for comparative analysis

## Key Findings
- **Strong Profitability**: Average monthly profit significantly exceeds $10K benchmark (p < 0.001)
- **Revenue-Profit Correlation**: 77.5% positive correlation between revenue and profit
- **Consistent Growth**: Year-over-year revenue and profit growth trends identified
- **Financial Stability**: Optimal debt-to-asset and current ratios maintained

## 🛠Technologies Used
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, SciPy
- **Statistical Analysis**: Hypothesis Testing (t-tests), Correlation Analysis, Descriptive Statistics
- **Data Visualization**: Line charts, Box plots, Heatmaps, Scatter plots
- **Environment**: Google Colab / Jupyter Notebook

## 📁 Repository Structure
```
├── data/
├── notebooks/
├── src/
├── results/
└── README.md

```

## Analysis Workflow

### Part 1: Descriptive Analysis & EDA
- **Data Cleaning**: Missing value treatment, outlier detection (IQR method), consistency validation
- **Descriptive Statistics**: Mean, median, mode, standard deviation calculations
- **Visualizations**: Revenue/expense trends, profit/cash flow distributions
- **Correlation Analysis**: Financial metrics relationship mapping

### Part 2: Inferential Analysis & Insights
- **Hypothesis Testing**: 
  - Monthly profit vs $10K benchmark (One-sample t-test)
  - Revenue vs expenses comparison (Paired t-test)
  - Business profitability assessment
- **Trend Analysis**: Year-over-year growth rate calculations
- **Financial Ratios**: Profit margin, debt-to-asset ratio, current ratio

## Statistical Results
| Test | T-Statistic | P-Value | Conclusion |
|------|-------------|---------|------------|
| Monthly Profit vs $10K | 10.93 | 5.56e-26 | Significantly > $10K |
| Revenue vs Expenses | 58.09 | ~0.0 | Significantly Different |
| Profitability Test | 58.09 | ~0.0 | Consistently Profitable |

## Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scipy
```

### Running the Analysis
1. Clone the repository
```bash
git clone https://github.com/yourusername/financial-health-analysis.git
cd financial-health-analysis
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the notebooks
```bash
jupyter notebook notebooks/01_descriptive_analysis.ipynb
```

## Key Insights & Business Recommendations
- Company demonstrates strong financial health with consistent profitability
- Revenue growth trends suggest sustainable business model
- Low debt-to-asset ratio indicates conservative financial management
- Recommend continued monitoring of cash flow volatility

## Contributing
Feel free to fork this project and submit pull requests for improvements.

