# House Price Prediction - DECCAN.AI Task

## 1. Introduction
Welcome! This project is part of the DECCAN.AI Machine Learning Engineer assessment. The goal is to build and deploy a model that predicts house prices based on various features like location, size, and amenities. By the end of this, you'll have a working ML model wrapped in an API, ready to take in house details and give back price predictions!

## 2. Data Preprocessing
To make our model accurate, we need to clean and prepare the data properly. Here's what we'll do:
- Load a publicly available dataset (like Kaggle's House Price Dataset or the California Housing Dataset).
- Handle missing values so our model isn't working with incomplete information.
- Scale and encode features to ensure consistency.
- Explore the data using visualizations to understand relationships between different factors.

## 3. Model Training & Evaluation
Once our data is ready, it's time to train the model. We'll:
- Split the data into training and test sets (usually 80% training, 20% testing).
- Train multiple regression models, including:
  - Linear Regression
  - Decision Tree
  - Random Forest
  - XGBoost
- Evaluate performance using key metrics like:
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R² Score (how well the model explains the variation in prices)
- Fine-tune the best model using GridSearchCV or RandomizedSearchCV.
- Save the best-performing model using Pickle or Joblib so we can use it later.

## 4. Model Deployment
Now that we have a trained model, we need to make it accessible. We'll:
- Build a REST API using FastAPI.
- Create an endpoint `/predict` where users can send house details as JSON and get price predictions in return.
- Test the API using Postman or CURL to ensure it works as expected.
## 5. Conclusion
That’s it! We built, trained, optimized, and deployed a machine learning model to predict house prices. We also explored Dockerization to make deployment smoother. Possible improvements include integrating more advanced models, deploying on cloud platforms like AWS, and adding a user-friendly frontend. 



