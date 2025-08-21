Credit Card Acquisition Forecasting (Forecasting & Automation)
Objective
Forecast the number of new credit card sign-ups based on marketing spend across different channels (TV, Radio, Newspaper). This project simulates how banks like Barclays optimize marketing budgets to acquire customers.

📊 Dataset

Advertising dataset (Kaggle)

TV → TV ad spend (in $000)

Radio → Radio ad spend (in $000)

Newspaper → Newspaper ad spend (in $000)

Sales → Customer sign-ups (in $000)

🔎 Exploratory Data Analysis

Correlation Heatmap shows TV spend has the highest impact (0.90) on Sales.

Scatter Plot (TV vs Sales) → Strong upward trend (more TV spending = higher customer acquisition).

⚙️ Models Used

Linear Regression

Train R²: 0.90, Test R²: 0.906

MAE: 1.27, RMSE: 1.71

Random Forest Regressor

Train R²: 0.991, Test R²: 0.953

MAE: 0.92, RMSE: 1.20

✅ Random Forest outperformed Linear Regression with higher accuracy and lower error.

📌 Output → If Company spends $200k on TV, $50k on Radio, $30k on Newspaper →
Predicted Sign-ups = 22.9k customers

💡 Key Insights

TV ads are the strongest driver of credit card acquisitions.

Radio ads have moderate influence.

Newspaper ads contribute the least.

Automated prediction function allows easy “what-if” analysis for future marketing strategies.
