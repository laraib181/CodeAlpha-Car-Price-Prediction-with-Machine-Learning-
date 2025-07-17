# 🚗 Car Price Prediction using Machine Learning

This project demonstrates how to build a **regression model** that predicts the price of a car based on various features using Python and machine learning techniques.

We perform **data preprocessing**, **feature engineering**, **visualization**, and train a **Linear Regression model** to evaluate performance using key metrics like MAE, MSE, and R².

---

## 📌 Project Goals

- Build a machine learning model to predict car prices.
- Handle missing values, categorical variables, and outliers.
- Apply feature scaling and encoding techniques.
- Evaluate model performance using regression metrics.

---

## 🛠️ Tools and Libraries

- **Python**
- **Pandas**: Data manipulation
- **Scikit-learn**: Model training & evaluation
- **Matplotlib** / **Seaborn**: Data visualization

---

## 📂 Project Structure
car-price-prediction/
│
├── car_price_prediction.ipynb # Jupyter notebook with code & analysis
├── README.md # Project documentation
├── requirements.txt # Python package dependencies

---

## 📊 Data Overview

Features used in the dataset may include (depending on source):
- Year
- Brand/Model
- Transmission
- Fuel Type
- Mileage
- Engine Size
- Number of Owners
- Car Type (SUV, Sedan, etc.)

---

## 🔄 Data Preprocessing

- Handled **missing values** and **duplicates**.
- Performed **label encoding** / **one-hot encoding** for categorical data.
- Scaled numerical features using **StandardScaler** or **MinMaxScaler**.
- Split data into **training** and **testing** sets (typically 80/20).

---

## 📈 Model Used: Linear Regression

A simple yet effective baseline model to predict continuous values.

### 🧪 Model Evaluation Metrics:

| Metric                 | Value              |
|------------------------|--------------------|
| **Mean Absolute Error** (MAE) | 2,154.75 |
| **Mean Squared Error** (MSE)  | 9,229,934.78 |
| **R² Score** (R-squared)      | 0.8831 |

> 📌 The R² value of **0.88** indicates that the model explains approximately 88% of the variance in car prices.

---

## 📉 Sample Visualizations

- **Correlation Heatmap**: Understand relationships between features
- **Distribution Plots**: Check skewness and outliers
- **Scatter Plot**: Visualize actual vs predicted prices

---

📚 Conclusion
This project demonstrates how basic regression techniques combined with proper feature engineering and preprocessing can be used to create a reliable car price prediction model.

While Linear Regression performed well (R² = 0.88), more advanced models like Random Forest or XGBoost can be explored for further improvement.
