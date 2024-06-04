# Telecom Customer Churn Prediction

## Overview

This project aims to predict customer churn for a telecom company using machine learning techniques. Customer churn, the phenomenon where customers discontinue using a company's services, can be predicted to identify at-risk customers and implement strategies to retain them.

## Dataset Description and Objective

### Dataset Description

The dataset contains information about telecom company customers, including demographics, subscribed services, tenure, payment method, and churn status.

### Objective

The objective of this analysis is to extract insights from the data and develop strategies to prevent customer churn. This involves data manipulation, visualization, and building predictive models.

## Methodology

### Data Preparation

- Loaded the dataset using Pandas.
- Conducted exploratory data analysis (EDA) to understand variable distributions and patterns.

### Data Preprocessing

- Removed duplicates and handled missing values.
- Performed label encoding to convert categorical variables into numerical format.
- Standardized numerical features using StandardScaler.

### Model Building

- Split the dataset into training and testing sets.
- Built three machine learning models: Logistic Regression, Decision Tree Classifier, and Random Forest Classifier.
- Evaluated model performance using accuracy, precision, recall, F1-score, and ROC-AUC metrics.
- Selected the best-performing model based on accuracy.

### Model Saving and Loading

- Saved the best-performing model using Joblib for scalability and reproducibility.
- Loaded the saved model to perform predictions on new data.

## Results

- Logistic Regression emerged as the best-performing model with an accuracy of 80%.
- Demographic factors, service preferences, contractual commitments, and financial implications were identified as key drivers of churn.
- Recommendations include leveraging data-driven insights for proactive retention strategies and continuously refining predictive models.

## Files Included

- `customer_churn.csv`: Dataset containing customer information.
- `customer_churn_prediction.ipynb`: Jupyter Notebook containing the Python code for data analysis, preprocessing, model building, evaluation, and model saving/loading.
- `customer_churn.pkl`: Saved machine learning model.
- `README.md`: This file providing an overview of the project, methodology, results, and files included.

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Open and run the `customer_churn_prediction.ipynb` notebook in Jupyter Notebook.
4. Follow the instructions in the notebook to explore the dataset, preprocess the data, build machine learning models, evaluate model performance, and save/load the model.
5. Modify the code as needed for your specific use case.

## Conclusion

In conclusion, the integration of EDA insights and predictive modeling emphasizes the significance of data-driven decision-making in addressing customer churn. By leveraging these insights and implementing proactive strategies, businesses can improve customer retention efforts, drive sustainable growth, and enhance their competitive edge in dynamic market environments.
