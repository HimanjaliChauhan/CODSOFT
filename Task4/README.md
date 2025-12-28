>Task 4: Sales Prediction 
>Objective: Predict product sales based on advertising spend (TV, Radio, Newspaper).
>Dataset: Advertising dataset (200 samples, 4 features)

> Approach
- Features: TV, Radio, Newspaper advertising spend ($K)
- Model: Linear Regression
- Evaluation: R² score, Mean Squared Error

>Key Insights
- Radio > TV > Newspaper impact on sales
- Strong linear relationship (R² > 0.90)

> Code Structure
1.Load advertising dataset
2.EDA + correlation analysis
3.Train/test split (80/20)
4.Linear Regression training
5.Model evaluation + feature importance
6.Predict sales for new ad budget

>Tech Stack: Python, scikit-learn, pandas, matplotlib, seaborn

