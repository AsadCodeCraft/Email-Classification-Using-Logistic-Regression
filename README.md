# Email Classification Project

This project aims to classify emails as either spam or ham (non-spam) using machine learning techniques. The project involves data preprocessing, model training using logistic regression, and analysis of the results.

## Introduction

Email classification is a common task in natural language processing (NLP) and machine learning. The ability to automatically categorize emails as spam or ham is essential for email filtering and prioritization.

## Main Objective

The main objective of this project is to develop a machine learning model that can accurately classify emails as spam or ham based on their content. By leveraging techniques such as text preprocessing, vectorization, and logistic regression, the goal is to achieve high accuracy in email classification.

## Dataset

The dataset used in this project is the Enron Email Dataset, specifically the enron1 subset. It contains a collection of emails categorized as spam and ham. The dataset is widely used in research and provides a diverse range of emails for training and evaluation.

## Getting Started

To run the project, follow these steps:

1. **Unzip the Dataset:** Unzip the `enron1.zip` file into the current directory.

2. **Data Preparation:** Traverse the dataset and create a Pandas dataframe. Reading emails from the 'spam' and 'ham' folders and storing them in a dataframe.

3. **Data Cleaning:** Perform data cleaning by normalizing text data. This involves removing non-alphabet characters and converting text to lowercase.

4. **Model Training (Logistic Regression):** Train a machine learning model using logistic regression. This step involves : 
   - splitting the dataset into train and test sets
   - vectorizing text data
   - fitting a logistic regression model
   - evaluating the model's performance

## Dependencies

- pandas
- scikit-learn
- matplotlib
