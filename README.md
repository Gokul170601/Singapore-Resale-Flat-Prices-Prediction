# Singapore  Resale Flat Prices Prediction

### App Live : https://singapore-resale-flat-prices-prediction-03q3.onrender.com

## 📘 Introduction
This project focuses on predicting the resale prices of Singapore flats using HDB data, leveraging the power of machine learning. The data undergoes thorough preprocessing, including handling outliers and encoding categorical features. I experimented with various regression models and selected the best performer, such as Random Forest. The user-friendly Streamlit application allows users to input features and receive real-time predictions, making it easier to explore and understand the housing market. Deployed on Render, it ensures easy access and smooth performance, empowering users to make informed decisions about flat resale prices in Singapore.

## Domain : 🏘️ Real Estate

## Data Source: https://beta.data.gov.sg/collections/189/view

## 🛠 Technology and Skills Takeaway
* Python
* Numpy
* Pandas
* Scikit-Learn
* Pickle
* Streamlit
* Render

## 📚 Packages and Libraries
```
!pip install numpy
!pip install pandas
!pip install scikit-learn
!pip install matplotlib
!pip install seaborn
!pip install streamlit
!pip install streamlit_option_menu
```

## 📘 Overview

### 🔁 Data Collection and Preprocessing
* Data Source : Downloaded historical resale flat data from official HDB sources, covering the period from 1990 to the current date.
* Initial Cleaning: Handled missing values, corrected inconsistencies, and ensured the data's integrity.
* Feature Engineering: Enhanced the dataset by creating new features and transforming existing ones to better capture the underlying patterns.

### 📊 Data Exploration and Handling
* Outlier Detection: Identified and handled outliers to ensure the model's robustness.
* Skewness Correction: Addressed skewed distributions using appropriate transformations.
* Categorical Encoding: Encoded categorical features using techniques like Label Encoding to convert them into numerical formats suitable for machine learning algorithms.

### 🤖 Model Selection and Training
* Cross-validated different regression models (e.g., Linear Regression, Random Forest Regressor, etc.)
* Evaluated performance metrics to choose the best model for predicting resale price.
* Selected the DecisionTree Regressor based on its superior performance in terms of R-squared and Mean Squared Error metrics.

### 💻 Model Deployment
* Model Serialization: Saved the trained DecisionTree Regressor model using pickle for later use in the application.
* Dashboard Development: Built an interactive dashboard using Streamlit to allow users to input relevant features and get predictions on flat resale prices.
* Deployed the application on Render for easy access and smooth performance.

### 👨‍🏫 Reference
* [Python Documentation](https://docs.python.org/3/)
* [pandas Documentation](https://pandas.pydata.org/docs/)
* [scikit-learn Documentation](https://scikit-learn.org/0.21/index.html)
* [numpy Documentation](https://numpy.org/doc/)
* [Streamlit Documentation](https://docs.streamlit.io/)


### 🎥 Demo Vide

YT Link :

### 📞 Contact
LINKEDIN: www.linkedin.com/in/gokul-m-j17/             
EMAIL : gokulgokul6847@gmail.com
