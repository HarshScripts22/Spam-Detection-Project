# Spam Mail Prediction

## Overview
This repository contains a machine learning project for classifying emails as spam or ham (not spam) using Logistic Regression. The project leverages a dataset from Kaggle and aims to accurately identify spam emails to help filter unwanted messages.

## Project Workflow
The project follows these key steps:

1. **Data Preprocessing:** Cleaning and preparing text data for analysis.
2. **Feature Extraction:** Using `TfidfVectorizer` to convert email content into numerical features.
3. **Model Building:** Implementing a Logistic Regression model for spam classification.
4. **Model Evaluation:** Assessing the model's performance using accuracy metrics on the test set.

## Dataset
The dataset used in this project is sourced from Kaggle. It consists of labeled email data indicating whether each message is spam or ham. The data is split into training and testing sets to evaluate the model effectively.

## Installation and Requirements
To run this project, you need the following Python packages:

```bash
pip install numpy pandas scikit-learn
