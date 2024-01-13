# Predicting-Housing-Prices

## Building regression model to predict housing prices based on various features like area, number of bedrooms, bathroom, etc.

# Author

Name: Jacinta Chioma Odirichukwu (PhD in Computer Science)
Phone: +2348153496082
Email: lmssmarthub@gmail.com


### Purpose
The House Price Prediction project aims to develop a regression model to predict housing prices based on various features such as area, number of bedrooms, bathrooms, and other relevant factors. This project is designed to assist buyers, sellers, and real estate professionals in making informed decisions during real estate transactions.

### Goals
1. **Predictive Modeling:** Develop a robust regression model that accurately predicts housing prices.
2. **User-Friendly Interface:** Provide a user-friendly interface for users to input property details and obtain price predictions.


### Key Features
- **Predictive Models:** Utilize various regression algorithms to determine the most effective model for predicting housing prices.
- **User Input:** Allow users to input property details through a user interface for instant predictions.
- **Data Visualization:** Include visualizations of key features and their impact on housing prices.
- **Model Evaluation:** Implement metrics to evaluate and compare the performance of different regression models.

### Setup, rerequisites, and Run Instructions

- Python 3.x
- Required Python packages, the Setup, rerequisites, and Run Instructions(specified in `docs/requirements.txt`)

Project Structure
The repository is organized as follows:

src/: Contains the source code for the project, the entire code in .ipynb ext.
dataset/: Directory the datasets.
docs/requirements.txt: Include documentation files, if any

1.  **Data Collection:** Download Dataset

To use this project, you need to download the dataset from the following URL:

[**Download Dataset**](https://www.kaggle.com/datasets/ashydv/housing-dataset)

Please ensure that you have the necessary permissions to access and use the dataset according to its licensing terms. Once downloaded, you can place the dataset file in the appropriate directory within your project.

2.  **Data Exploration:** Explored the dataset to understand its structure, features, and distributions.
Identified potential relationships between features and the target variable (price).
3. **Data Preprocessing:** Handled missing values, eliminated duplicates, and encoded categorical variables.
Ensured data cleanliness and prepared it for modeling.
4. **Feature Engineering:** Created new features and selected relevant ones to enhance model performance.
Utilized techniques like SelectKBest to choose top features.
5. **Undersampling and Oversampling:** Balanced the imbalanced target variable using RandomUnderSampler and RandomOverSampler.
Investigated the impact of class distribution on model performance.
6. **Regression Modeling:** Explored different regression algorithms such as Random Forest, Linear Regression, Least Angle Regressor, DecisionTreeRegressor, Ridge Regression, Support Vector Regression (SVR), K-Nearest Neighbors (KNN).
Evaluated model performance using metrics like Mean Squared Error, Root Mean Squared Error, and R-squared.
7. Model Evaluation and Comparison:
Compared and analyzed the performance of different regression models.
Explored the impact of feature importance on predictive accuracy.
8. Vizualized the performance using pyplot from matplotlib (matplotlib.pyplot)
8. Model Deployment:
Deployed the selected model for live predictions using Django framework.
Integrated the model into a web application accessible through endpoints.

### Conclusion
Proficiency in data preparation, feature engineering, model selection, and implementation is demonstrated by the House Price Prediction project. It serves as a thorough illustration of end-to-end machine learning development and has the potential to be improved upon and used in practical situations.

