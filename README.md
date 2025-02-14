# US Home Price Analysis (2003–2024)

This project analyzes the factors influencing US home prices over the last 20 years using publicly available data. The analysis includes data cleaning, exploratory data analysis (EDA), and a linear regression model to identify key drivers of home prices.

---

## **Project Overview**
- **Objective**: Identify and quantify the impact of key macroeconomic factors on US home prices.
- **Dependent Variable**: S&P Case-Shiller Home Price Index (`CSUSHPISA`).
- **Independent Variables**:
  - 30-Year Fixed Mortgage Rate (`MORTGAGE30US`)
  - Unemployment Rate (`UNRATE`)
  - Housing Supply (`MSACSR`)
  - Building Permits (`PERMIT`)
  - Consumer Price Index (`CPIAUCSL`)
- **Data Source**: [FRED (Federal Reserve Economic Data)](https://fred.stlouisfed.org/).

---

## **Repository Structure**
home_price_analysis/
├── data/
│   ├── raw/           # Original CSV files from FRED
│   └── processed/     # Cleaned, merged dataset (cleaned_data.csv)
├── notebooks/
│   └── home_price_analysis.ipynb  # Full code (EDA, modeling, plots)
├── reports/
│   └── Home_Price_Analysis_Report.pdf  # 1-page summary of findings
├── plots/             # Visualizations (PNG/PDF)
└── README.md          # Instructions to reproduce results


---

## **Key Findings**
1. **CPI (Inflation)**:
   - Strongest positive correlation with home prices (`0.88`).
   - Rising inflation leads to higher home prices.
2. **Unemployment**:
   - Strongest negative correlation with home prices (`-0.57`).
   - Higher unemployment reduces home prices.
3. **Mortgage Rates**:
   - Moderate negative correlation (`-0.25`).
   - Higher rates reduce affordability, lowering home prices.
4. **Housing Supply**:
   - Weak negative correlation (`-0.22`).
   - Increased supply reduces prices, but the effect is less pronounced.

---

## **Visualizations**
### 1. Home Prices vs CPI (2003–2024)
![Home Prices vs CPI](plots/home_prices_vs_cpi.png)

### 2. Correlation Heatmap
![Correlation Heatmap](plots/correlation_heatmap.png)

### 3. Scatter Plots
- **Home Prices vs Unemployment**:
  ![Home Prices vs Unemployment](plots/home_prices_vs_unemployment.png)
- **Home Prices vs Housing Supply**:
  ![Home Prices vs Housing Supply](plots/home_prices_vs_housing_supply.png)

---

## **How to Reproduce**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/home_price_analysis.git
   cd home_price_analysis
