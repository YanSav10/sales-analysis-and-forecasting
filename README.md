# Sales Analysis and Forecasting Project

## Overview
This project is focused on analyzing sales data, forecasting future trends, and providing actionable insights for strategic decision-making. Using advanced machine learning techniques and visualization tools, the project addresses sales volume forecasting, market classification, stock management, and brand performance evaluation.

---

## Features

### 1. **Data Analysis**
   - Review and cleaning of actual sales data from 2023–2024.
   - Seasonality assessment, identifying trends and peak sales periods.

### 2. **Forecasting Models**
   - **LSTM**: Predicts sales volumes with seasonality consideration.
     - **Performance Metrics**:
       - MAE: 85.13
       - RMSE: 364.68
       - R²: 0.82
   - **Prophet**: Analyzes trends and seasonality.
     - **Performance Metrics**:
       - MAE: 1.02
       - RMSE: 1.23
       - R²: 1.00
   - **XGBoost**: Classifies markets into high, medium, and low sales volume categories.
     - **Performance Metrics**:
       - Accuracy: 1.00
       - F1-Score for all classes: 1.00

### 3. **Stock Analysis**
   - Identification of distributors with low stock levels (<25% of initial stock).
   - Recommendations for replenishment.

### 4. **Brand Performance**
   - Analysis of top-performing and underperforming brands across markets.
   - Suggestions to improve weaker brands using strategies from successful ones.

---

## Visualizations
The project includes detailed visualizations built using Tableau:
1. **Depletion Trends**:
   - Sales trends over time.
   - Seasonal patterns analysis.
2. **Market Classification**:
   - Market class distribution by state and year.
   - Market class percentages for each state.
3. **Stock Analysis**:
   - Replenishment needs per distributor.
   - Distribution of low-stock scenarios across markets.
4. **Brand Insights**:
   - Top-performing brands by sales volume.
   - Distribution of brand performance across markets.

---

## Key Recommendations
### Meeting the Plan for Underperforming Brands, Markets, and Distributors:
- **For Brands**:
  - Boost visibility via digital campaigns and promotional offers.
  - Expand distribution networks.
- **For Markets**:
  - Conduct region-specific campaigns and introduce localized products.
  - Strengthen distributor partnerships with performance incentives.
- **For Distributors**:
  - Provide targeted training and data-driven support to improve performance.

### Enhancing Market Penetration:
- Broaden the product portfolio to attract diverse customer segments.
- Leverage predictive analytics for seasonal stock management.
