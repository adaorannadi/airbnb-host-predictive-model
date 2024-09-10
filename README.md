# airbnb-host-predictive-model

## TO VIEW THE CODE DOWNLOAD THE HTML FILE

This repository contains Python htmls that detail a project predicting Airbnb prices and classifying whether an Airbnb host is likely to be a superhost or not. The repository is divided into two main sections: one for regression (price prediction) and the other for classification (superhost classification).

Regression Problem: Airbnb Price Prediction
The regression problem aims to predict the price of an Airbnb listing based on various features such as location, property type, amenities, and host attributes. The dataset consists of historical Airbnb listings with features such as latitude, longitude, neighborhood, property type, number of bedrooms, bathrooms, beds, host response rate, acceptance rate, and more. Through exploratory data analysis (EDA), insights were gathered by analyzing missing values, correlations, and distributions of features. Key steps included handling missing data, transforming categorical variables, and identifying important predictors.

Data cleaning involved converting data types, handling missing values, and encoding categorical variables. Feature engineering was performed to create new features and transform existing ones for better model performance. Features were selected based on correlation analysis and domain knowledge. Polynomial features were generated to capture nonlinear relationships. An ElasticNetCV regression model was employed for feature selection and prediction. The model was evaluated using root mean squared error (RMSE) on the training data, providing insights into the model's predictive accuracy and generalization capabilities.

Classification Problem: Superhost Classification
The classification problem aims to classify whether an Airbnb host is likely to be a superhost based on various features such as amenities, host attributes, and property type. Similar to the regression problem, the dataset includes features relevant to superhost classification. EDA was performed to understand feature distributions and correlations with the target variable (superhost status). Data cleaning involved handling missing values, encoding categorical variables, and feature engineering. Logistic regression was chosen as the classification model due to its simplicity and interpretability. Model performance was evaluated using accuracy score on the training data.

Conclusion
This repository provides end-to-end solutions for both Airbnb price prediction and superhost classification problems. Users can leverage the provided code and datasets to develop and evaluate their own regression and classification models for similar tasks. The scripts and datasets are organized in a structured manner, making it easy to understand and replicate the analysis.
