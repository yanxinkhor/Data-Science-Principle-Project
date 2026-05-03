# Data-Science-Principle-Project
This project focuses on building a model for detecting suspicious transaction that might indicate money laundering cases in Malaysia

in this study, the SAML-D dataset(https://www.kaggle.com/datasets/berkanoztas/synthetic-transaction-monitoring-dataset-aml), that contains approximately 9.5 million transaction records, will be utilised.

## Project Objectives
- Identify patterns associated with suspicious financial transactions using preprocessing and EDA.
- Build two predictive classification models.
- Compare machine learning models to determine a suitable classification approach.

## Methods Used
### Data Preprocessing
- Perform random sampling of 200,000 records from the original dataset to minimise running time
- Use the resampling method to handle class imbalance
- Feature engineering based on transaction time
- Log transformation to reduce skewness
- One-hot encoding for categorical variables

### Exploratory Data Analysis (EDA)
EDA was conducted to identify common money laundering behaviours, including:
- cross-border transactions
- unusually frequent receiver accounts
- flagged transaction patterns

### Machine Learning Models
Two supervised learning models were developed and evaluated, including XGBoost and Random Forest



