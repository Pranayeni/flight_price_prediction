# ✈️ Flight Price Prediction using Machine Learning

##  Project Overview
This project predicts flight ticket prices based on different factors such as airline, source city, destination city, departure time, arrival time, duration, total stops, and journey date using Machine Learning algorithms.

The main goal of this project is to help users estimate flight prices before booking tickets.

---
| Feature         | Description           |
| --------------- | --------------------- |
| Airline         | Name of the airline   |
| Date_of_Journey | Journey date          |
| Source          | Departure city        |
| Destination     | Arrival city          |
| Route           | Flight route          |
| Dep_Time        | Departure time        |
| Arrival_Time    | Arrival time          |
| Duration        | Total travel duration |
| Total_Stops     | Number of stops       |
| Additional_Info | Extra information     |
| Price           | Flight ticket price   |


##  Features
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Model Training
- Flight Price Prediction
- Model Evaluation
- Deployment Ready Structure

---

##  Tech Stack

### Programming Language
- Python

### Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---
## Exploratory Data Analysis (EDA)

Performed detailed data analysis including:

Airline-wise price comparison
Source & destination analysis
Duration analysis
Stops vs Price analysis
Correlation heatmaps
Outlier detection

--
###  Data Preprocessing
Steps Performed
Handling missing values
Converting date & time columns
Feature extraction
Label Encoding
One-Hot Encoding
Feature Scaling

--
## Machine Learning Models Used

The following algorithms were tested:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor
- Model Evaluation

--
## Evaluation Metrics Used:

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score
  
--
## 📂 Project Structure

```bash
Flight_Price_Prediction/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── Flight_Price_Prediction.ipynb
│
├── models/
│   └── model.pkl
│
├── app.py
├── requirements.txt
├── README.md
└── screenshots/
