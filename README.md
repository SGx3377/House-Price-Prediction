# House Price Prediction in Bengaluru

Welcome to the House Price Prediction project! This repository contains all the code and resources used to predict house prices in Bengaluru, India. Using a comprehensive dataset, we have performed extensive Exploratory Data Analysis (EDA), data cleaning, feature engineering, and applied various linear regression models to achieve an accurate prediction of house prices. Read on to learn more about our approach and findings.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
  - [1. Exploratory Data Analysis (EDA)](#1-exploratory-data-analysis-eda)
  - [2. Data Cleaning](#2-data-cleaning)
  - [3. Feature Engineering](#3-feature-engineering)
  - [4. Model Building and Evaluation](#4-model-building-and-evaluation)
- [Best Model](#best-model)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Predicting house prices accurately is crucial for buyers, sellers, and real estate agents. In this project, we use a dataset of house prices in Bengaluru to build a predictive model. The best model we found is a linear regression model with an accuracy of 85%.

## Dataset

The dataset consists of various features such as location, size, price, number of bedrooms, bathrooms, and more. It provides a comprehensive view of the housing market in Bengaluru.

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

We start with a thorough EDA to understand the dataset better:
- Visualize distributions and relationships between variables.
- Identify patterns and trends in the data.
- Detect outliers and anomalies.

### 2. Data Cleaning

Data cleaning steps include:
- Handling missing values.
- Removing duplicates.
- Correcting inconsistent data entries.

### 3. Feature Engineering

Feature engineering is crucial to improve model performance:
- Creating new features from existing ones.
- Encoding categorical variables.
- Normalizing numerical features.

### 4. Model Building and Evaluation

We used various linear regression models and fine-tuned them using GridSearchCV:
- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet Regression

After evaluating all models, the best model was found to be a simple Linear Regression model.

## Best Model

The best model is a **Linear Regression** model, achieving an accuracy of **85%**. This model outperformed other variants, proving to be the most effective for our dataset.

## Results

The Linear Regression model predicts house prices with high accuracy. This model can be used by real estate professionals and enthusiasts to make informed decisions in the Bengaluru housing market.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/SGx3377/House-Price-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd house-price-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

After installing the dependencies, you can run the project using the following command:
```bash
python main.py
```
This will execute the data processing, model training, and prediction steps.

## Contributing

We welcome contributions to improve this project. Feel free to fork the repository, make your changes, and submit a pull request. Please ensure your contributions are well-documented and tested.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Thank you for visiting our project! We hope this repository helps you understand and predict house prices in Bengaluru effectively. Happy coding!
