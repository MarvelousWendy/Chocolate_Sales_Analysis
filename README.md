# 🍫 Chocolate Sales: Data Analysis & Machine Learning

## 📌 Overview

This project explores chocolate sales data through **exploratory data analysis (EDA)** and builds **machine learning models** to uncover patterns and make predictions. It combines visualization, feature engineering, and multiple modeling techniques to generate business insights.

---

## 📂 Project Structure

```
├── Chocolate_Sales.ipynb   # Main notebook with EDA and modeling
├── data/
│   ├── calendar.csv        # Date-related information
│   ├── customers.csv       # Customer details
│   ├── products.csv        # Product catalog
│   ├── sales.csv           # Sales transactions (main dataset)
│   └── stores.csv          # Store/location information
├── README.md               # Project documentation
```

---

## ⚙️ Technologies Used

* **Python**
* **Data Analysis:** pandas, numpy
* **Visualization:** matplotlib, seaborn, plotly
* **Machine Learning:** scikit-learn, xgboost

---

## 🔍 Key Steps

### 1. Data Loading & Cleaning

* Import dataset
* Handle missing values
* Encode categorical variables
* Feature scaling (StandardScaler / MinMaxScaler)

### 2. Exploratory Data Analysis (EDA)

* Distribution plots 📊
* Correlation analysis
* Sales trends and patterns
* Interactive visualizations using Plotly

### 3. Feature Engineering

* Label encoding
* Normalization / standardization
* Selection of relevant features

### 4. Machine Learning Models

The project experiments with multiple models:

* Linear Regression
* Logistic Regression
* Decision Trees
* Random Forest
* Gradient Boosting
* XGBoost

### 5. Model Evaluation

* Train/test split
* Cross-validation
* Performance metrics (accuracy, RMSE, etc.)

---

## 📈 Results & Insights

* Identifies key factors influencing chocolate sales
* Compares performance across models
* Highlights the most predictive features

---

## 🧠 Future Improvements

* Hyperparameter tuning
* Deployment (e.g., Streamlit app)
* More advanced feature engineering
* Time-series modeling
