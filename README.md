# 🚗 Car Price Predictor using Machine Learning

## 📌 Overview

This project is a Machine Learning-based **Car Price Predictor** that estimates the selling price of a used car based on its specifications. The model is trained on a cleaned **Used Car (Quikr) Dataset** and is deployed as a web application using **Flask**, allowing users to enter car details and receive an instant price prediction.

---

## 🎯 Features

The prediction is based on the following car attributes:

- Car Company
- Car Model
- Manufacturing Year
- Fuel Type
- Kilometers Driven

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Flask
- HTML
- CSS
- Bootstrap
- Pickle

---

## 🔄 Project Workflow

- Imported the required Python libraries.
- Loaded and explored the used car dataset.
- Cleaned the dataset by handling missing values, removing invalid entries, and converting data into appropriate formats.
- Performed Exploratory Data Analysis (EDA) to understand feature relationships.
- Encoded categorical features using One-Hot Encoding.
- Split the dataset into training and testing sets.
- Created a Machine Learning Pipeline using ColumnTransformer and Linear Regression.
- Evaluated the model using the R² Score.
- Saved the trained model using Pickle.
- Designed a responsive user interface using HTML, CSS, and Bootstrap.
- Integrated the trained Machine Learning model with the Flask application to predict used car prices based on user inputs.

---

## 📊 Learning Outcomes

This project helped me understand the complete Machine Learning workflow, including:

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Feature encoding using One-Hot Encoding
- Model training using Linear Regression
- Model evaluation using R² Score
- Machine Learning Pipeline creation
- Model serialization using Pickle
- Flask web application development

---

## 🚀 Future Enhancements

- Improve prediction accuracy using advanced Machine Learning algorithms such as Random Forest, XGBoost, or Gradient Boosting.
- Deploy the application on cloud platforms such as Render, Railway, or Heroku.
- Add support for additional car features such as transmission type, ownership history, mileage, and engine capacity.
- Improve the user interface with a modern and responsive design.
- Enable users to compare predicted prices of multiple cars.
  
