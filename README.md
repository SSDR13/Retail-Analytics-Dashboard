# 📊 Retail Analytics Dashboard - Power BI

![Dashboard Preview](Retail-Analytics-Dashboard-Image.png)

## 🔍 Project Overview
An interactive dashboard analyzing sales performance with:
- **Key Metrics**: Avg Profit per Order, Sales per Customer (DAX measures)
- **Top 5 Products**:  Isolated top-selling products
- **Dynamic Filters**: Region, Category, and time-period slicers

## 🛠️ Technical Details
- **Tools**: Power BI (DAX, Data Modeling, Interactive Visuals)
- **Dataset**: [Kaggle Superstore Data](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) (Public)
- **DAX Measures**:
  ```dax
  Avg Profit per Order = DIVIDE(SUM('Orders'[Profit]), COUNTROWS('Orders'), 0)
  Sales per Customer = DIVIDE(SUM('Orders'[Sales]), DISTINCTCOUNT('Orders'[Customer ID]), 0)
  ```

## 📂 How to Use
1. Download `Retail_Analytics_Dashboard.pbix`.
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/).
3. Interact with filters to explore trends.

## 💡 Key Insights
- Isolated top-selling products, revealing **$153K in concentrated revenue** and 12% higher unit sales than average.
- Automated profit tracking with DAX measures (`Profit per Order`), enabling rapid performance reviews. 
- **Avg profit per order**: $28.66  
- **Sales per customer**: $2.90
