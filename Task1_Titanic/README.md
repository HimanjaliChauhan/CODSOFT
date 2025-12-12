>Task 1 — Titanic Survival Prediction

>Objective
Build a machine learning model to predict whether a passenger survived the Titanic disaster based on features such as age, sex, class, fare, and family details.

> Dataset
Seaborn Titanic dataset 

>Steps Followed
1. Exploratory Data Analysis (EDA)
   - Checked missing values
   - Analyzed survival patterns by sex and passenger class
   - Visualized distributions and relationships using countplots

2. Data Cleaning
   - Filled missing `age` values using median
   - Filled missing `embarked` values using mode
   - Converted `sex` to numeric labels (male = 0, female = 1)
   - One-hot encoded `embarked` column

3. Model Building
   - Split data into training and testing sets (80/20)
   - Applied Logistic Regression model (`sklearn`)
   - Trained the model on cleaned data

4. Evaluation
   - Calculated accuracy score
   - Generated confusion matrix and classification report
   - Accuracy Achieved: 0.8100558659217877

>Key Insights
- Female passengers had significantly higher survival rates.
- 1st class passengers had better chances of survival compared to 2nd and 3rd class.

>Files Included
- `Task1_Titanic.ipynb` — full notebook with code and outputs  
- `requirements.txt` — libraries used  
- `screenshots/` — plots and confusion matrix used for demonstration  

>Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  


