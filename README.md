# 🍕 Dominos---Predictive-Purchase-Order-System

# 📌 Project Overview

- This project focuses on building a Predictive Purchase Order System for Dominos using historical pizza sales data and ingredient information. The goal is to forecast future sales, estimate the required ingredients, and generate a purchase order to optimize inventory management, reduce waste, and streamline supply chain operations.

# 🚀 Skills Takeaway

🔹 Data Cleaning & Preprocessing

🔹 Exploratory Data Analysis (EDA)

🔹 Time Series Forecasting

🔹 Predictive Modeling

🔹 Business Decision Making

🔹 Real-world Application of Data Science


# 🏭 Domain
Food Service Industry

#❓ Problem Statement

Dominos wants to enhance its supply chain by predicting future pizza sales and automatically generating purchase orders for required ingredients. By forecasting sales accurately, Dominos can:

- Ensure the right inventory levels.

- Avoid overstocking and wastage.

- Prevent stockouts and delivery delays.

- Improve overall operational efficiency.

# 💼 Business Use Cases

✅ Inventory Management: Maintain ideal stock levels based on predicted demand.

✅ Cost Reduction: Minimize waste and unnecessary storage costs.

✅ Sales Forecasting: Understand demand trends to plan promotions and resource allocation.

✅ Supply Chain Optimization: Automate ingredient ordering to reduce manual errors and delays.


# 🧭 Approach

# 1. Data Preprocessing and Exploration

- Removed missing and inconsistent values.

- Parsed date fields and created relevant time-based features.

- Visualized sales patterns to identify trends and seasonality.

# 2. Sales Prediction

- Feature Engineering:

    - Day of the week

    - Month

    - Is weekend/holiday/promo period
 
- Modeling:

    - Selected SARIMA as the final time series model based on performance.

    - Trained the model on daily aggregated total_price data.

- Evaluation:

- Metrics used:

    - MAE: 342.13

    - RMSE: 572.05

    - MAPE: 14.98%

# 3. Purchase Order Generation

- Forecasted sales for the next 30 days using SARIMA.

- Mapped pizzas to their ingredients using a cleaned ingredient dataset.

- Calculated required ingredient quantities based on predicted pizza sales.

- Generated a Purchase Order CSV summarizing ingredient needs.

# 📊 Results

✅ Accurate 30-day pizza sales forecasts.

✅ MAPE: 14.98% (Acceptable for real-world applications).

✅ A detailed purchase order CSV containing ingredient-wise quantities for the predicted period

# 🧰 Tech Stack & Tools

# Category	                 - Tools/Libraries Used
- Data Manipulation	         - Pandas, NumPy
- Visualization	             - Matplotlib, Seaborn
- Modeling	                 - statsmodels (SARIMA), sklearn
- Forecasting	             - SARIMA
- Notebook & Scripts	     - Jupyter Notebook, Python (.py)
- Files Processed	         - Processed Pizza Sales, Ingredient Dataset
- Output	                 - Sales Forecasts, Purchase Order (CSV)
