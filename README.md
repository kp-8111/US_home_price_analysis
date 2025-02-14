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

---


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
![Home Prices vs CPI](Outputs/Line_chart.png)

### 2. Correlation Heatmap
![Correlation Heatmap](Outputs/Corelation_heat_map.png)

### 3. Scatter Plots
- **Home Prices vs CPI (Inflation)**:
  ![Home Prices vs Inflation](Outputs/scatter_plot_1.png)
- **Home Prices vs Unemployment**:
  ![Home Prices vs Unemployment](Outputs/scatter_plot_3.png)
- **Home Prices vs Housing Supply**:
  ![Home Prices vs Housing Supply](Outputs/scatter_plot_2.png)

---


