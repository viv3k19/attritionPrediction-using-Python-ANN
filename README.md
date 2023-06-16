# Customer Attrition Prediction Using Artificial Neural Network (ANN)
Customer attrition, also known as churn, is a significant challenge for businesses in various industries. It refers to customers discontinuing their relationship or subscription with a company. Predicting customer churn is crucial for businesses to address customer needs, minimize losses, and optimize retention strategies.

In this project, we focus on customer attrition prediction in the telecom industry. By utilizing an Artificial Neural Network (ANN), a powerful deep learning model, we aim to develop a predictive model that effectively identifies customers at risk of churn. Through precision, recall, and F1-score metrics, we evaluate the model's performance and gain insights into its predictive capabilities.

Accurate customer churn prediction enables telecom companies to take proactive measures such as tailored retention strategies, improved service quality, and targeted promotions. This enhances customer satisfaction, profitability, and overall business success.

Our project covers the entire process of attrition prediction, including data loading, preprocessing, model building, and evaluation. Additionally, we visualize the data to better understand the patterns and factors contributing to customer churn.

## Dataset
The dataset used for this prediction task is stored in the file attritionData.csv. It contains information about customers, including their demographics, services subscribed, and churn status.

## Prerequisites
Before running the code, make sure you have the following dependencies installed:

`pandas`
`matplotlib`
`numpy`
`scikit-learn`
`seaborn`
`tensorflow`

You can install these dependencies using pip:
```shell
pip install pandas matplotlib numpy scikit-learn seaborn tensorflow
```

## Usage
Download the dataset attritionData.csv and place it in the same directory as this script.
Run the code in an environment that supports Jupyter notebooks or Python scripts.

## Steps 
* Load the dataset using pandas.
* Preprocess the data by converting relevant columns to numeric format and handling missing values.
* Visualize the data to gain insights into customer churn patterns.
* Further preprocess the data by encoding categorical variables and scaling numeric features.
* Split the dataset into training and testing sets.
* Build an ANN model using TensorFlow/Keras.
* Train the model on the training data.
* Evaluate the model's performance on the testing data.
* Predict churn for the testing data using the trained model.
* Generate a classification report to assess the model's performance.
* Visualize the confusion matrix to analyze the predictions.

## Results

![results](https://github.com/viv3k19/attritionPrediction-using-Python-ANN/assets/82309435/cfdba498-1a4f-4300-a524-aaf7d82ac6ca)


## Analytics

* Visualization

![visualization](https://github.com/viv3k19/attritionPrediction-using-Python-ANN/assets/82309435/202cef55-6214-4db2-84d0-8c794d7a4566)

* Confusion Matrix

![confusionMatrix](https://github.com/viv3k19/attritionPrediction-using-Python-ANN/assets/82309435/8f72c329-7053-423f-baf8-48ea879ac9be)

# Project Creator
* Vivek Malam - Feel free to contact me at viv3k.19@gmail.com for any questions or feedback.
