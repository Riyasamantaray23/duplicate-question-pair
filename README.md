# Quora Duplicate Question Pair Detection

This project is an end-to-end natural language processing (NLP) solution developed to accurately identify and classify duplicate questions on the Quora platform. Using machine learning models, the application aims to streamline the user experience by reducing duplicate content.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Deployment](#deployment)
- [License](#license)

## Project Overview

The Quora Duplicate Question Pair Detection project focuses on determining whether two questions asked on Quora are semantically identical. The solution involves gathering diverse question pairs, performing data preprocessing, feature engineering, model training, and finally deploying the model as a cloud-based web application.

## Features

- **Data Collection**: Utilizes a dataset of diverse question pairs from Quora for training and testing.
- **Data Preprocessing**: Implements rigorous data cleaning and preprocessing steps, including:
  - Tokenization
  - Lowercasing
  - Stop word removal
  - Stemming and lemmatization
- **Feature Engineering**: 
  - Transformation and scaling of features
  - Bag of Words model creation
  - Encoding categorical variables
- **Exploratory Data Analysis (EDA)**: Provides insights into the dataset through visualizations and statistical analysis.
- **Model Training**: Trains multiple machine learning models, achieving high accuracy using:
  - Random Forest
  - XGBoost
- **Performance Metrics**: Evaluates model performance using accuracy, precision, recall, and F1-score.
- **Web Application**: Deploys the trained model as a user-friendly cloud-based application, allowing users to easily check for duplicate questions.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: 
  - Pandas
  - Matplotlib
  - Scikit-Learn
  - XGBoost
- **Deployment**: Cloud platform (e.g., Heroku, AWS, or any preferred service)

