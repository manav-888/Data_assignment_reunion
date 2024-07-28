# Data_assignment
# Problem 4: Machine Learning

![Screenshot 2024-07-28 at 2 25 24 PM](https://github.com/user-attachments/assets/16a0f14b-7762-4d4f-9d28-91d83f27fc48)

## Applicant Data Overview:
Total Entries : 1000  
Features: 15 (5 numerical, 10 categorical)  
Missing Values columns : Has_been_employed_for_at_least, Has_been_employed_for_at_most, Telephone, Savings_account_balance, Balance_in_existing_bank_account_(lower_limit_of_bucket), and Balance_in_existing_bank_account_(upper_limit_of_bucket).  


## Loan data Overview :

![Screenshot 2024-07-28 at 2 32 05 PM](https://github.com/user-attachments/assets/5894620c-d8c1-4816-a2ef-06f2494c15c6)

Total Entries: 1000  
Features: 13 (8 numerical, 5 categorical)  
Missing Values columns : Purpose, Property, and Other_EMI_plans

## Handling Missing Values
For categorical features with missing values :  imputing with the mode .  
For numerical features with missing Values : imputing with the mean or median.

##  Handling Categorical Features  
Encode categorical features using label encoding based on the number of unique values.  

## Compute the correlation matrix  
![Screenshot 2024-07-28 at 2 43 29 PM](https://github.com/user-attachments/assets/2ea144ba-ae44-4f48-9ae9-e8ed43cbc0a4)  

## Handling  highly Correlated Features

Drop highly correlated features to prevent multicollinearity.

# Model Training   
## Model Selection  
We will train at two machine learning models to predict the credit risk:  
Logistic Regression: For its simplicity and interpretability.  
Random Forest: For handling non-linear relationships and interactions.  


# Training and Evaluation   
1) Train the models and evaluate their performance using accuracy, precision, recall, and F1-score.
2) perform hyperparameter tuning to optimize model performance.  
3) Train the model with best params and evaluate their performance using accuracy, precision, recall, and F1-score



