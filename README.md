# Amazon Sales Analysis & Machine Learning

This project focuses on analyzing **Amazon Sales Report** data and applying **Machine Learning models** to extract meaningful insights and predictions.  
It covers **EDA, Visualization, Classification, and Regression** in one complete workflow.

---

## Project Overview
1. **Data Understanding**  
   - Columns explored: Order ID, Date, Status, Fulfilment, Sales Channel, Category, Size, Courier Status, Qty, Amount, Shipping details, B2B, etc.  
   - Column explanation provided for clarity.  

2. **Exploratory Data Analysis (EDA)**  
   - Checked dataset structure, missing values, and unique values.  
   - Performed summary statistics for sales amount, quantity, and orders.  
   - Derived new features: `month`, `year`, `day_of_week`.  

3. **Data Visualization (Key Charts)**  
   - Sales Contribution by Channel (Pie Chart)  
   - Order Status % Share (Pie/Donut Chart)  
   - Daily Sales Trend (Line Chart)  
   - B2B vs Non-B2B Sales Share (Pie Chart)  
   - Courier Status Distribution (Bar Chart)  
   - Sales by Order Status (Bar Chart)  
   - Sales by Day of Week (Bar Chart)  
   - Monthly Sales Trend (Line Chart)  
   - Sales by Category (Bar Chart)  
   - Order Status Donut Chart  
   - Sales Share by Country (Pie Chart)  
   - Sales vs Postal Code (Scatter Plot)  
   - Orders Count by Day of Week (Bar Chart)  
   - Sales by Size (Bar Chart)  
   - Sales Amount Distribution by Category (Boxplot)  
   - Distribution of Sales Amount (Histogram)  

   ✅ Charts improved with professional styling (colors, labels, grids, overlap-free text).  
   ✅ Each chart accompanied with **short description/insights**.  

4. **Machine Learning**  
   - **Classification (Order Status Prediction)**  
     - Features: Fulfilment, Sales Channel, Category, Size, State, B2B  
     - Model: Random Forest Classifier  
     - Metrics: Accuracy, Classification Report, Confusion Matrix  

   - **Regression (Sales Amount Prediction)**  
     - Features: Fulfilment, Sales Channel, Category, Size, State, B2B, Qty  
     - Model: Random Forest Regressor  
     - Metrics: RMSE ≈ 209, R² ≈ 0.41  

5. **Insights**  
   - Sales trend varies by category, size, and fulfillment method.  
   - Weekend orders tend to be higher.  
   - Cancellation rate visible in order status % share.  
   - Classification model achieved good accuracy for predicting order status.  
   - Regression model explained ~41% variance, scope for improvement with advanced models (XGBoost/LightGBM).  

---

## 📦 Libraries Used
- **pandas** → Data manipulation  
- **numpy** → Numerical operations  
- **matplotlib** → Visualization  
- **seaborn** → Advanced plots  
- **scikit-learn** → Machine learning models & evaluation  

---

