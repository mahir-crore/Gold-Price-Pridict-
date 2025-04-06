# Gold Price Prediction 📊

This is a simple machine learning project where I built a regression model to predict gold prices using historical financial data.

The notebook is designed to be interactive — the user can upload their own dataset (in the same format as `gld_price_data.csv`) and select a regression model of their choice: **Random Forest**, **Decision Tree**, or **Support Vector Regression (SVR)**.

---

## 🔧 Features

- Upload your own `.csv` file (no hardcoded data).
- Choose from 3 different regression models.
- Train the selected model and evaluate it with R² and Mean Squared Error.
- Visualize actual vs predicted gold prices using line plots.

---

## 🧠 Models Used

- RandomForestRegressor  
- DecisionTreeRegressor  
- SVR (Support Vector Regressor)

---

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Upload your dataset when prompted.
4. Select the model (1/2/3) when asked.
5. Check the evaluation metrics and plot at the end.

---

## 📁 Dataset Info

The dataset is expected to have the following columns (excluding nulls):

- `Date`
- `GLD` (Gold price)
- Other financial indicators like SPX, USO, SLV, etc.

> *Make sure your dataset follows the same structure as the original `gld_price_data.csv` file.*

---
