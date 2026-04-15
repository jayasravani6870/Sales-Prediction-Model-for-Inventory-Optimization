# Sales Prediction Model for Inventory Optimization

## Problem
Retail businesses often face losses due to overstocking and understocking. Accurate sales prediction is essential for efficient inventory management and demand planning.

## Solution
Developed a machine learning pipeline using the BigMart dataset to predict product-level sales across different outlets. The model leverages features such as product price (Item MRP), outlet type, and visibility.

## Results
- Achieved strong predictive performance based on R2 score
- Decision Tree outperformed Linear Regression by capturing non-linear patterns
- Identified key drivers of sales such as Item MRP and Outlet Type

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Project Workflow
1. Data Cleaning & Missing Value Handling  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Model Building (Linear Regression, Decision Tree)  
5. Model Evaluation & Comparison  

## Key Insights
- Sales are positively correlated with Item MRP  
- Supermarket outlets generate higher sales than grocery stores  
- Promotional and location factors significantly influence demand  

## Business Impact
- Helps businesses optimize inventory and reduce waste  
- Supports better demand forecasting  
- Improves decision-making for pricing and stocking  

## How to Run
1. Clone the repository  
2. Install required libraries (`pip install -r requirements.txt`)  
3. Open and run the notebook  

## Project File
- `sales_prediction_model.ipynb` – Complete implementation with EDA, modeling, and evaluation
