# A-simple-regression-problem-predicting-the-lifespan-of-some-metal-alloys
The following regression problem is to find a model that can learn and predict the lifespan of a series of metal alloys from a synthetic data set.
## Exploratory Data Analysis

Exploratory data analysis was performed to understand the dataset and improve data quality. This included identifying potential outliers, examining the distribution of numerical features, and reviewing minimum and maximum values to detect anomalies and data inconsistencies.

## Data Preprocessing

Categorical features were encoded using One-Hot Encoding to convert them into a machine-readable format. Numerical features were normalized using Min-Max scaling after exploratory analysis to ensure consistent feature ranges and improve model performance.

## Model Training and Comparison

Two models were trained and evaluated: a Neural Network and a Random Forest classifier. Both models achieved very similar performance after testing, with a slight advantage observed for the Random Forest.

For the Random Forest model, two categorical features were encoded using label encoding instead of one-hot encoding, as tree-based models can handle ordinal feature representations effectively without requiring binary expansion.
