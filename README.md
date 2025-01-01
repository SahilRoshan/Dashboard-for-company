# Plant Co. Quantity Performance Dashboard

This repository contains the **Plant Co. Quantity Performance Dashboard**, which provides insights into the quantity performance metrics, profitability segmentation, and product trends for Plant Co.. Below is a detailed explanation of the dashboard and its components.
![Screenshot 2025-01-01 222412](https://github.com/user-attachments/assets/752b259c-eaf7-473f-894f-6a921d46fb38)

---

## Dashboard Overview

The dashboard visualizes key metrics such as year-to-date (YTD) quantity, profitability (GP%), and performance comparison with the previous year (PYTD). It highlights data trends, product segmentation, and country-wise contributions to performance.

### Key Metrics:
- **YTD Quantity**
- **YTD vs PYTD Difference**
- **PYTD Quantity**
- **Gross Profit Percentage (GP%)**

---

## Dashboard Components

### 1. **Bottom 10 YTD vs PYTD (Country)**
- **Purpose**: Highlights the bottom 10 countries in terms of performance (YTD vs PYTD).
- **Key Insights**:
  - China (-9.76K) and France (-9.36K) experienced the most significant negative differences.
  - Other notable underperforming countries include Sweden, Greece, and Japan.

### 2. **Quantity YTD vs PYTD | Month - Country - Product**
- **Purpose**: Tracks monthly performance trends across countries and products.
- **Visualization**:
  - Green bars indicate an increase in performance compared to PYTD.
  - Red bars indicate a decrease in performance.
- **Key Trends**:
  - Notable improvements in March (+12K) and June (+13K).
  - Declines observed in September (-8K) and November (-4K).

### 3. **Quantity YTD vs PYTD | Month (Product Type)**
- **Purpose**: Displays monthly product type performance trends.
- **Insights**:
  - Breakdown of product types: Indoor, Landscape, Outdoor.
  - Consistent growth in certain months, with spikes in April and October.

### 4. **Account Profitability Segmentation (GP% and Quantity)**
- **Purpose**: Analyzes account profitability by comparing GP% against quantity.
- **Visualization**:
  - Scatter plot with GP% on the Y-axis and Value YTD on the X-axis.
  - Identifies accounts with higher profitability and quantity correlations.

---

## Technology Stack
- **Data Visualization**: Microsoft Power BI
- **Data Source**: Business intelligence tools and Plant Co.'s internal performance database
- **Languages**: N/A (visualization-driven)

---

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo-name/plant-co-dashboard.git
   ```

2. Access the Power BI dashboard file (as provided) or view the provided visualizations in the repository.

3. Analyze the insights:
   - Identify trends and insights for product performance.
   - Focus on countries or product types needing improvement.

---

## Key Insights and Recommendations
- Focus on **underperforming countries** (e.g., China, France) to understand the root causes of declines.
- Leverage **monthly trends** to identify peak performance periods and replicate success factors in low-performing months.
- Use **profitability segmentation** to prioritize high GP% accounts and optimize resource allocation.

---

## Future Enhancements
- Integration with real-time data sources for live updates.
- Adding drill-through capabilities for product-specific analysis.
- Enhanced filtering options for deeper insights.

---

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
