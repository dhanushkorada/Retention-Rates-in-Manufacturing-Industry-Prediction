# Retention Rates Prediction in Manufacturing Industry

Welcome to the Recruitment and Retention Prediction project for the manufacturing industry. This project focuses on predicting employee retention rates using machine learning techniques to help manufacturing companies better understand and manage their workforce.

## Table of Contents

- [Introduction](#introduction)
- [Setup and Required Installs](#setup-and-required-installs)
- [Data Generation and Preprocessing](#data-generation-and-preprocessing)
- [Machine Learning Models](#machine-learning-models)
- [Selected Model](#selected-model)
- [Results and Insights](#results-and-insights)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction

Employee retention is a critical challenge in the manufacturing industry. High turnover rates can disrupt operations, impact productivity, and increase costs. This project aims to develop a machine learning model that predicts employee retention rates based on various factors such as compensation, workplace safety, promotion potential, and more. By identifying the key drivers of retention, manufacturing companies can implement targeted strategies to improve employee satisfaction and retention.

## Setup and Required Installs

To run the project, you need to set up your environment and install the required dependencies:

1. Clone this repository:

git clone https://github.com/dhanushkorada/recruitment-retention-prediction.git
cd recruitment-retention-prediction

2. Install the required dependencies:

pip install -r requirements.txt


## Data Generation and Preprocessing

The dataset used for this project is generated with random values for the independent variables. The provided code snippet in the repository demonstrates how the data is generated, cleaned, and preprocessed for analysis.

## Machine Learning Models

Several regression models are tested to predict employee retention rates:

- Linear Regression
- Random Forest Regression
- K-Nearest Neighbors Regression (KNN)
- Support Vector Regression (SVR)
- Decision Tree Regression

## Selected Model

After evaluating the performance metrics (MSE, MAE, RMSE), the Linear Regression model is chosen as the optimal model due to its accuracy in predicting retention rates.

## Results and Insights

The results of the Linear Regression model are discussed and visualized in the Jupyter Notebook provided in the repository. The notebook provides insights into the relationships between various factors and employee retention rates.

## Conclusion

The Recruitment and Retention Prediction model developed in this project offers valuable insights for manufacturing companies to enhance their workforce management strategies and reduce attrition. By understanding the factors influencing retention, companies can implement targeted initiatives to create a positive work environment and retain valuable employees.

## License

This project is licensed under the [MIT License](LICENSE).
