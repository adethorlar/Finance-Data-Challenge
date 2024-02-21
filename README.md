# Credit Card Fraud Detection: Finance Data Challenge

### Overview
This project aims to tackle one of the most prevalent issues in the financial sector: credit card fraud. With over $180 million in losses annually and affecting at least 26% of the US adult population, credit card fraud represents a significant challenge that requires sophisticated solutions. This project utilizes historical credit card transaction data to build a fraud detection and monitoring system that can identify fraudulent activities with high accuracy.

### Project Structure
The project consists of a comprehensive Jupyter Notebook (Finance_Data_Challenge.ipynb) that outlines the entire process of data preprocessing, feature engineering, model training, and evaluation.

### Data
The dataset comprises historical credit card transactions from 2,000 customers, totaling 6.8 million transactions spanning from January 2016 to December 2019. The challenge involved merging three distinct datasets to form a comprehensive dataset with 45 columns. Key steps in data preparation included:
- Geocoding zip codes to include merchant and customer locations.
- Handling missing values, particularly for transactions without a 'Merchant State'.
- Encoding categorical variables and the target column for fraudulent transactions.

### Preprocessing
Several preprocessing steps were undertaken to prepare the data for modeling:
- Conversion of transaction times and amounts to appropriate data types.
- Creation of new features such as credit limit utilization percentage and the distance between merchants and customers.
- Application of oversampling with Synthetic Minority Over-sampling Technique (SMOTE) to address class imbalance.

### Conclusion
This project provides a robust framework for credit card fraud detection, leveraging advanced machine learning techniques to identify fraudulent transactions effectively. The proposed solution addresses the critical need for financial institutions to mitigate fraud-related losses and enhance customer trust and security.
