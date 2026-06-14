# -Machine-Learning-for-Cafe-Sales-Item-Prediction
# Overview
This project predicts which menu item a customer will buy using a dirty cafe sales dataset. 
Two classification models (Logistic Regression and Random Forest) were compared.

# Tools
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

# Key Results
Best Model: Random Forest (76% accuracy, 76% F1-score)

Perfectly classified: Coffee, Cookie, Salad, Tea

Challenging items: Cake, Juice, Sandwich, Smoothie (similar price points)

Top features: Price Per Unit, Total Spent, Month, Day_of_Week

# Key Challenges Fixed
Data leakage (removed Quantity & Price Per Unit for regression; kept for classification)

Missing values (dropped Location at 40%, created 'Missing' category for Payment Method)

Placeholder errors ("ERROR", "UNKNOWN" replaced with NaN)

# Files
model_training.ipynb - Model training and evaluation
dirty_cafe_sales.csv
report.pdf - Full project report
