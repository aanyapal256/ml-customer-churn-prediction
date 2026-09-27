Designed a ML model to predict customer churn using there previous activities.The model is created using real world Telco customer data and Logistic Regression and GridSearchCv.

TECHNOLOGIES USED:
python
Pandas
Numpy
Matplotlib
Seaborn
Skcikit-Learn
Google Colab 

The dataset contains customer information including:

- Customer demographics
- Account information
- Services used
- Contract details
- Monthly charges
- Total charges
- Churn status

PROJECT WORKFLOW:

Data Loading 
Data exploration
Data conversion 
Missing values detection 
Handling Missing values
Feature encoding
Independent and Dependent Feature selection 
Train test split
Logistic Regression
Hyperparameter Tuning using GridSearchCv
Model prediction
Model evaluation
Data visualization 

GridSearchCV was used to test different combinations of:

- 'C'
- 'penalty'
- 'solver'
- 'max_iter'
- 'class_weight'

The model was evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score

The project can be extended by:

- Comparing multiple classification algorithms
- Applying advanced hyperparameter tuning
- Using larger real-world datasets
- Developing customer retention strategies
- Using additional customer behaviour features
