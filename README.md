# HR Analytics Job Prediction
This project uses machine learning to predict employee turnover based on various factors such as satisfaction level, last evaluation, number of projects, monthly working hours, tenure, work accidents, promotions, salary, and department. The prediction model is built using a Naive Bayes classifier, and a Streamlit app is provided for easy interaction with the model.

## Project Overview
The project includes the following main components:

- Data Analysis and Visualization: Analyze and visualize the dataset to understand trends and relationships between features.
- Model Training: Train several machine learning models to predict whether an employee will leave or stay, and evaluate their performance.
- Streamlit App: A user-friendly web application to interact with the model and make predictions.

## Models Used
The following models were trained and evaluated:

- Logistic Regression
- Support Vector Classifier (SVC)
- Gaussian Naive Bayes (Final Model)
  
The Gaussian Naive Bayes model was chosen for deployment due to its performance.

## Files
- data_analysis_and_modeling.ipynb: Jupyter notebook containing data analysis, visualization, and model training.
- streamlit_app.py: Streamlit app for making predictions.
- naive_bayes_model.pkl: Trained Naive Bayes model saved using Pickle.
- requirements.txt: List of required packages.

## Results
The Naive Bayes model achieved an accuracy of 84% on the test dataset.
