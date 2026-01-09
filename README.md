# Income_activities_using_Machine_Learning
Final Year Project – Income Activities Using Machine Learning

This project is my **final year machine learning project** focused on analyzing and predicting income-related activities using supervised learning techniques.

The complete workflow — from data loading and preprocessing to model training and saving — is implemented in a **single Jupyter Notebook** for simplicity and clarity.

---

## Project Overview

The goal of this project is to build a machine learning model that can analyze income activity data and make predictions based on input features.

The project demonstrates:
- Data preprocessing
- Exploratory data analysis
- Machine learning model training
- Model evaluation
- Saving the trained model using Pickle for future use

---

## Files in This Repository

- `Untitled.ipynb`  
  Jupyter Notebook containing the complete machine learning pipeline:
  - Data loading
  - Preprocessing
  - Model training
  - Model evaluation
  - Model serialization

- `dbo_incomes.csv`  
  Dataset used for training and testing the machine learning model.

- `rf.pkl`  
  Serialized (pickled) trained machine learning model generated at the end of the notebook.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Seaborn / Matplotlib
- Pickle

---

## Machine Learning Model

- Algorithm used: **Random Forest Classifier**
- The model is trained on the provided dataset and saved as a `.pkl` file.
- The saved model can be loaded later for inference without retraining.
