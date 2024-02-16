# Credit Card Customer Segmentation Analysis
![banner](https://github.com/kjellrkri/Portfolio/blob/main/Credit%20Card%20Clustering%20Analysis/credit%20card%20clustering%20analysis%20banner.png)
## Overview

This project aims to develop customer segmentation to define marketing strategy for a credit card company. The dataset used for analysis summarizes the usage behavior of approximately 9000 active credit card holders over the last 6 months. The dataset consists of 18 behavioral variables recorded at a customer level.

## Dataset Information

The dataset used for this analysis is sourced from Kaggle and can be found [here](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata).

### Data Dictionary

- **CUST_ID**: Identification of Credit Card holder (Categorical)
- **BALANCE**: Balance amount left in the account to make purchases
- **BALANCE_FREQUENCY**: How frequently the Balance is updated (score between 0 and 1, where 1 = frequently updated, 0 = not frequently updated)
- **PURCHASES**: Amount of purchases made from the account
- **ONEOFF_PURCHASES**: Maximum purchase amount done in one-go
- **INSTALLMENTS_PURCHASES**: Amount of purchase done in installment
- **CASH_ADVANCE**: Cash in advance given by the user
- **PURCHASES_FREQUENCY**: How frequently the Purchases are being made (score between 0 and 1, where 1 = frequently purchased, 0 = not frequently purchased)
- **ONEOFFPURCHASESFREQUENCY**: How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
- **PURCHASESINSTALLMENTSFREQUENCY**: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
- **CASHADVANCEFREQUENCY**: How frequently the cash in advance is being paid
- **CASHADVANCETRX**: Number of Transactions made with "Cash in Advanced"
- **PURCHASES_TRX**: Number of purchase transactions made
- **CREDIT_LIMIT**: Limit of Credit Card for the user
- **PAYMENTS**: Amount of Payment done by the user
- **MINIMUM_PAYMENTS**: Minimum amount of payments made by the user
- **PRCFULLPAYMENT**: Percent of full payment paid by the user
- **TENURE**: Tenure of credit card service for the user

## Project Goals

The primary goals of this project are as follows:
1. Perform exploratory data analysis (EDA) to gain insights into the credit card dataset.
2. Preprocess the data to prepare it for clustering analysis.
3. Apply various clustering algorithms to segment customers based on their credit card usage behavior.
4. Evaluate the performance of the clustering algorithms and interpret the results.
5. Derive actionable insights and recommendations for the credit card company based on the clustering analysis.

## Usage

- The main script for conducting the clustering analysis is provided in the Jupyter Notebook file [credit_card_clustering_analysis.ipynb](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata).
- Explore the results and visualizations generated during the analysis to understand the customer segmentation.


## Analysis Steps

1. Data Loading and Exploration
2. Data Preprocessing
3. Exploratory Data Analysis
4. Clustering Algorithm Selection
5. Model Training and Evaluation
6. Interpretation of Clusters
7. Marketing Strategy Recommendation

## Dependencies

- Python 3.x
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn

## Conclusion

This project aims to provide valuable insights into the customer segmentation of the credit card company, ultimately assisting in targeted marketing strategies, personalized customer experiences, and business growth.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

[Kjell Randby Kristensen]
