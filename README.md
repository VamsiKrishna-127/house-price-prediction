# 🏡 House Price Prediction using Machine Learning

This project aims to predict house prices using a regression model trained on a dataset containing various attributes of residential properties. The goal is to create a robust model that helps buyers, sellers, and real estate professionals make informed decisions based on accurate price estimations.

## 📁 Dataset

The dataset (`data.csv`) includes multiple features such as:

* **Area (sqft)**
* **Number of Bedrooms (BHK)**
* **Number of Bathrooms**
* **Location**
* **Balconies**
* **Total Floors**
* **Availability (Ready to Move/Under Construction)**
* **Price (Target Variable)**

> 🗂️ The dataset is cleaned and preprocessed to remove inconsistencies such as missing values, outliers, and duplicate records.

## 🔧 Technologies Used

* **Python**
* **Pandas & NumPy** – Data manipulation and analysis
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Machine learning models and tools
* **Jupyter Notebook** – Interactive development environment

## 🧠 Machine Learning Pipeline

1. **Data Preprocessing**

   * Handling missing values
   * Encoding categorical variables
   * Feature engineering
   * Outlier detection

2. **Exploratory Data Analysis (EDA)**

   * Correlation analysis
   * Price trends by location, BHK, area, etc.

3. **Model Training**

   * Linear Regression
   * Decision Tree Regressor
   * Random Forest Regressor
   * Gradient Boosting

4. **Evaluation Metrics**

   * Mean Absolute Error (MAE)
   * Root Mean Squared Error (RMSE)
   * R² Score

5. **Model Selection**

   * Comparison of models based on performance metrics
   * Cross-validation for robustness

## 📊 Results

* Achieved **R² Score: \~0.85** (depending on feature selection and model)
* Random Forest and Gradient Boosting performed the best among tested algorithms

## 🚀 Future Work

* Hyperparameter tuning using GridSearchCV
* Deployment as a Flask web app or Streamlit dashboard
* Incorporate geospatial data (e.g., proximity to landmarks, public transport)
* Use advanced models like XGBoost or LightGBM

## 📂 Folder Structure

```
├── data.csv
├── house_price_prediction.ipynb
├── requirements.txt
├── README.md
```

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/house-price-prediction.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook house_price_prediction.ipynb
```

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or pull requests to improve the project
