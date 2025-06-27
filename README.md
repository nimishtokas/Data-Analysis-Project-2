# 🛒 BlinkIT Grocery Sales Forecasting & Dashboard Analysis
This project involves analyzing and predicting sales patterns for an Indian online grocery retailer, BlinkIT, using a combination of exploratory data analysis (EDA), machine learning, and interactive Power BI dashboards.

📌 Project Objective

To analyze historical sales data and build a robust machine learning model that predicts product-level sales across different store types and item categories. The project also includes the creation of a Power BI dashboard for interactive business insights.

🎯 Key Tasks

- Data cleaning and preprocessing of raw BlinkIT grocery dataset

- Exploratory data analysis (EDA) to understand key sales drivers

- Feature engineering and transformation

- Model building using Random Forest and GridSearchCV for hyperparameter tuning

- Model evaluation using R² score and RMSE

- Visualization of actual vs. predicted sales

- Business insight reporting via Power BI dashboard

🧪 Steps Taken

1. Data Cleaning
- Imputed missing values in Item Weight

- Standardized inconsistent values in Item Fat Content

- Dropped irrelevant or redundant columns (e.g., Rating)

2. Feature Engineering
- Created outlet age from Outlet Establishment Year

- One-hot encoded categorical variables

- Built interaction features like MRP × Visibility

3. Modeling
- Trained a Random Forest Regressor as baseline model

- Performed hyperparameter tuning using GridSearchCV

- Applied log transformation to address skew in target variable

4. Evaluation
- R² score plateaued at ~0.55, indicating moderate predictive ability

- Created scatter plots of actual vs. predicted sales

- Identified top features: Item MRP, Outlet Type, Item Visibility

5. Visualization
- Developed a Power BI dashboard for business users:

- Sales by category and outlet

- Outlet-type performance

- Interactive filters for exploration

📈 Results

- Best-performing model: Tuned Random Forest Regressor

- R² Score: 0.55 — indicating the model captures 55% of sales variability

- Business Insight: Sales are most strongly driven by item pricing and outlet type; however, absence of promotions, stock data, and time series limits predictive accuracy

📚 Conclusion

While the model provides useful insights into sales drivers, its predictive power is constrained by limited feature diversity. Future performance could be enhanced by incorporating:

- Temporal data (week, seasonality)

- Promotion and discount flags

- Inventory availability

- Customer-level segmentation
