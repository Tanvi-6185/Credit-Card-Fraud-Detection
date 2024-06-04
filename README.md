# Credit-Card-Fraud-Detection
Credit Card Fraud Detection Model Implemented using Machine Learning In Python

import numpy as np
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score

# loading the dataset to a Pandas DataFrame
credit_card_data = pd.read_csv('/content/credit_data.csv')

# first 5 rows of the dataset
credit_card_data.head()

credit_card_data.tail()
# dataset informations
credit_card_data.info()
# checking the number of missing values in each column
credit_card_data.isnull().sum()

# distribution of legit transactions & fraudulent transactions
credit_card_data['Class'].value_counts()

print(legit.shape)
print(fraud.shape)

# statistical measures of the data
legit.Amount.describe()

X = new_dataset.drop(columns='Class', axis=1)
Y = new_dataset['Class']
print(Y)



