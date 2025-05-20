# 💎 Diamond Price Prediction

This project uses machine learning to predict diamond prices based on features like carat, cut, color, clarity, and dimensions.

## 🔍 Dataset
- Source: Kaggle Diamond Dataset
- ~54,000 rows
- Features: `carat`, `cut`, `color`, `clarity`, `x`, `y`, `z`, etc.
- Target: `price`

## 🛠️ Process Overview
1. Data Cleaning (missing values, zero-dimension removal)
2. Feature Engineering (label encoding, normalization)
3. Outlier Handling (IQR method)
4. Model Building:
   - 🔹 Linear Regression
   - 🌲 Random Forest Regressor
5. Evaluation:
   - MAE and MSE used for performance comparison
   - Random Forest performed better

## 🖥️ Deployment
The trained model predicts price based on user input (e.g., carat, cut, etc.) using a code-based UI.

## 📊 Results
- Random Forest MAE: 271
- Random Forest MSE: 303,910

## 📷 Screenshots
Include image files like:
- `mlr_eval.png`
- `rf_eval.png`
- `regression_plot.png`
