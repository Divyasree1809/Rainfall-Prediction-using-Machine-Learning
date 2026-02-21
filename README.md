# 🌧 Rainfall Prediction using Machine Learning

This project focuses on building a **Machine Learning model** to predict whether it will rain or not based on various atmospheric conditions.

Rainfall prediction is traditionally performed by meteorological experts, but machine learning models can analyze historical weather patterns and make accurate predictions automatically.


## 🎯 Project Objective

To develop a classification model that predicts:

* 🌤 **0 → No Rainfall**
* 🌧 **1 → Rainfall**

based on atmospheric features such as temperature, humidity, cloud cover, wind speed, and pressure.



## 📊 Dataset Information

Dataset: `Rainfall.csv`

* 📦 Total Records: **366**
* 📈 Total Columns: **12**

### Features:

| Feature       | Description              |
| ------------- | ------------------------ |
| day           | Day of observation       |
| pressure      | Atmospheric pressure     |
| maxtemp       | Maximum temperature      |
| temperature   | Average temperature      |
| mintemp       | Minimum temperature      |
| dewpoint      | Dew point                |
| humidity      | Humidity level           |
| cloud         | Cloud cover              |
| rainfall      | Target variable (yes/no) |
| sunshine      | Sunshine hours           |
| winddirection | Wind direction           |
| windspeed     | Wind speed               |


## 🛠 Technologies & Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Imbalanced-learn (Imblearn)



## 🚀 Possible Improvements

* Collect larger dataset
* Hyperparameter tuning
* Cross-validation
* Feature engineering
* Try ensemble models
* Deploy using Streamlit or Flask
* Add weather API for real-time prediction

