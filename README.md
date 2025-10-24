# Bitcoin Trading Sentiment Analysis

## Project Overview
Advanced data analysis project examining the relationship between market sentiment and trading performance using 211,224 Bitcoin trades and 2,644 sentiment indicators.

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/pandas-data%20analysis-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-notebook-orange)
![License](https://img.shields.io/badge/license-MIT-green)


## 📊 Key Findings

### Statistical Results
- **Correlation Analysis**: Sentiment vs PnL = -0.083 (p-value: 0.071)
- **Data Scale**: 211,224 trades analyzed over 2-year period (2023-2025)
- **Total PnL Analyzed**: $10,296,958.94

### Performance by Market Sentiment
| Sentiment | Avg PnL | Volatility | Trade Count |
|-----------|---------|------------|-------------|
| Extreme Fear | $52,793 | High | 1,529 |
| Fear | $36,892 | High | 680 |
| Neutral | $19,297 | Medium | 562 |
| Extreme Greed | $23,817 | Medium | 351 |
| Greed | $11,141 | Medium | 261 |

### Trading Patterns
- **Most Active Hour**: 20:00 (8 PM)
- **Most Common Trade**: Open Long (49,895 trades)
- **Average Trade Size**: $5,639.45
- **Total Fees**: $245,857.72

## 🛠 Technical Implementation

### Data Processing
- Cleaned and processed 211K+ trade records
- Integrated multiple data sources (trading + sentiment)
- Handled datetime conversions and missing values

### Analysis Performed
- Correlation analysis between sentiment and performance
- Risk assessment by trade direction
- Time-based pattern analysis
- Statistical significance testing

### Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Statistical analysis (SciPy)
- Data visualization
- Jupyter Notebooks

## 📈 Business Insights

### Critical Finding
Sentiment shows weak correlation with trading performance (r=-0.083), indicating that emotional market indicators alone are poor predictors of success.

### Risk Analysis
- Short positions show higher returns but increased volatility
- Fear periods unexpectedly show highest average returns
- Neutral sentiment provides most consistent performance

## 🗂 Project Structure
```
ds_analysis/
├── notebook_1.ipynb
├── csv_files/
│   ├── bitcoin_sentiment.csv
│   ├── trader_data.csv
│   └── processed_data.csv
├── outputs/
│   ├── eda_sentiment.png
│   ├── eda_trader.png
│   ├── sentiment_vs_pnl.png
│   ├── leverage_vs_sentiment.png
│   └── correlation_heatmap.png
└── reports/
```

## 🎯 Value Delivered

### Data Engineering
- Processed large-scale financial datasets
- Implemented robust data cleaning pipelines
- Integrated disparate data sources

### Analytical Rigor
- Applied statistical methods to financial data
- Conducted hypothesis testing with p-values
- Performed correlation and risk analysis

### Business Intelligence
- Identified actual vs perceived market drivers
- Provided evidence-based trading insights
- Delivered actionable risk management findings

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

### Running the Analysis
1. Place CSV files in `csv_files/` directory
2. Execute `notebook_1.ipynb` sequentially
3. Review generated visualizations in `outputs/`
4. Check processed data in `csv_files/processed_data.csv`

## 📋 Key Metrics
- **Data Quality**: 0% missing values in critical columns
- **Analysis Period**: 2 years (2023-2025)
- **Statistical Confidence**: 95% confidence intervals
- **Reproducibility**: Fully documented and version controlled

## 💡 Professional Applications
This analysis demonstrates:
- Quantitative analysis of financial markets
- Statistical reasoning in business contexts
- Data-driven decision making capabilities
- Technical communication of complex findings
