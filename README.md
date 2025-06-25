# 📈 Tourist Footfall Prediction (Time Series Forecasting)

This notebook implements a time series forecasting pipeline to predict monthly tourist footfall in Shimla, India. It combines statistical modeling with dimensionality reduction to provide insights into seasonal tourism trends.

---

## 🧠 Project Overview

The notebook includes the following steps:

* Loading and cleaning monthly tourist data
* Exploratory Data Analysis (EDA)
* Decomposing the time series into trend, seasonality, and residuals
* Performing PCA for dimensionality reduction on exogenous features
* Training a SARIMAX model for forecasting
* Evaluating predictions using RMSE and MAE

---

## 🛠️ Tech Stack

* **Language:** Python
* **Notebook:** Jupyter (main.ipynb)
* **Libraries:**

  * `pandas`, `numpy` – Data processing
  * `matplotlib`, `seaborn` – Visualization
  * `statsmodels` – SARIMAX modeling
  * `sklearn` – PCA and evaluation

---

## 🔍 Highlights

* Real tourist data from Shimla, India
* Monthly analysis with trend and seasonality extraction
* PCA used to reduce feature dimensionality before forecasting
* SARIMAX model fitted with exogenous inputs
* Evaluation metrics for assessing forecast quality

---

## 📂 How to Run

1. Install required libraries using pip:

   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
   # Install any other libraries/packages used
   ```
2. Open the `main.ipynb` file in Jupyter Notebook or any IDE that supports notebooks.
3. Run all cells in order for a full demonstration.

---

## 📊 Sample Outputs

* Line plots for trends and seasonal components
* PCA-transformed variable plots
* Forecast vs Actual footfall comparisons
* Error metrics: RMSE, MAE

---

## 🚫 Limitations & Future Work

* Currently limited to Shimla data; model may need tuning for other regions
* Include weather, holidays, and event data for more accurate modeling
* High number of outliers due to covid
---

