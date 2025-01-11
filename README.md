# EcomX CLV Prediction

## Objective
This project aims to predict Customer Lifetime Value (CLV) for EcomX Retailers, a mid-sized online retailer, to identify high-value customers and optimize marketing and retention strategies.

---

## Dataset
- **Customers Data**: Includes customer demographics and tenure.
- **Transactions Data**: Contains transaction details and product categories.
- **Engagement Data**: Tracks customer interactions (site visits, email engagement).
- **Marketing Data**: Details on campaigns and customer responses.

---

## Tools & Techniques
- **Language**: Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- **Feature Engineering**:
  - Early behavior indicators (e.g., early spending, early frequency, early recency).
  - Normalized monetary value based on customer tenure.
- **Models**:
  - Linear Regression
  - K-Nearest Neighbors (KNN)
- **Evaluation Metrics**: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)

---

## Key Insights
1. **Early Spending Predicts CLV**:
   - Customers spending >$200 in the first 30 days have an average CLV of $140,644.97.
2. **High Transaction Frequency Matters**:
   - Customers with >5 transactions in 30 days have an average CLV of $133,000.65.
3. **Engagement Metrics Are Critical**:
   - Frequent site visitors (>10 visits/month) and email responders (>5 emails opened) show higher CLV.

---

## Recommendations
1. **Target High-Value Customers**:
   - Personalized loyalty programs for customers spending >$200 in their first 30 days.
2. **Enhance Engagement**:
   - Incentivize site visits and email interactions with exclusive offers.
3. **Optimize Early Interactions**:
   - Focus marketing resources on high-frequency and high-value customer segments.

---

## Business Impact
- **Quantitative**:
  - A 5% retention improvement for high-value customers could increase revenue by ~$154,402.
- **Qualitative**:
  - Enhanced customer satisfaction and loyalty, improving brand reputation and ROI.

---

## Files
1. **Jupyter Notebook**: [DataScience_A2.ipynb](./DataScience_A2.ipynb)
2. **Summary Report**: [PDF](./MBAN%20DS%20Summary%20Report%20Assignment%202.pdf)
3. **Datasets**:
   - [customers_final.csv](./customers_final.csv)
   - [transactions_final.csv](./transactions_final.csv)
   - [engagements_final.csv](./engagements_final.csv)
   - [marketing_final.csv](./marketing_final.csv)

---

## How to Use
1. Download the Jupyter Notebook and datasets.
2. Run the notebook to reproduce the analysis and results.
3. Refer to the summary report for detailed insights and recommendations.
