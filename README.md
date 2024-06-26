# Financial-Fraud-Detection
The project focuses on detecting financial fraud using machine learning algorithms. It utilizes a Kaggle dataset containing transaction data from a financial service company. 

[Dataset Link](https://www.kaggle.com/datasets/sriharshaeedala/financial-fraud-detection-dataset)

# Project Overview:
The project focuses on detecting financial fraud using machine learning algorithms. It utilizes a Kaggle dataset containing transaction data from a financial service company. Exploratory Data Analysis (EDA) techniques such as correlation plot and count plot were employed to gain insights into the data, revealing that fraud primarily occurs through transfer and cash-out transactions rather than payment, cash-in, and debit transactions. Subsequently, two machine learning models, logistic regression, and random forest, were developed to predict fraudulent transactions.

# Business Problem Addressed:
The project addresses the critical issue of financial fraud, which poses significant risks to financial institutions and customers. By accurately identifying fraudulent transactions, financial service companies can implement proactive measures to prevent fraud, safeguard their assets and maintain customer trust. Utilizing machine learning algorithms for fraud detection enables the automation of this process, allowing for timely detection and prevention of fraudulent activities.

# Project Implementation:
Implement the project using Python scripts or Jupyter Notebooks.

The project involves the following steps:

- Data Exploration and Analysis (EDA): Explore the dataset, analyze features, and visualize data using correlation plots and count plots to identify patterns and trends related to 
  fraudulent transactions.

- Data Preprocessing: Prepare the data for modelling by handling missing values, encoding categorical variables, and splitting the dataset into training and testing sets.

- Model Development: Develop machine learning models, such as logistic regression and random forest, to predict fraudulent transactions based on the available features.

- Model Evaluation: Evaluate the performance of the models using accuracy scores and cross-validation scores to assess their effectiveness in detecting fraudulent transactions.

- Interpretation and Deployment: Interpret the results of the models and consider deploying the best-performing model to detect fraudulent transactions in a real-world financial system.

# Detailed Code:
The code is structured to perform the following tasks:

1. **Data Loading and Exploration**:
   - Load the dataset.
   - Explore basic information about the dataset such as data types, missing values, and the distribution of fraud and legitimate transactions.

2. **Data Preprocessing**:
   - Drop unnecessary columns like 'nameOrig' and 'nameDest'.
   - Create a balanced sample dataset with an equal number of legitimate and fraudulent transactions.

3. **Data Visualization**:
   - Visualize the correlation between features using a heatmap.
   - Plot the count of different transaction types against fraud status.

4. **Model Training and Evaluation**:
   - Split the data into training and testing sets.
   - Train a Logistic Regression model on the training data and evaluate its performance on both training and testing data.
   - Perform cross-validation on the Logistic Regression model.
   - Again, Train a Random Forest Classifier and evaluate its performance, including confusion matrix visualization and cross-validation.


