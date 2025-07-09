# 🏠 House Price Prediction ML Project

This mini project builds a regression model to predict house prices using a real-world housing dataset.

## 📊 Dataset Overview
- **Rows**: 187,531
- **Columns**: 21
- Target: `Price (in rupees)`
- Features: Numerical + Categorical

## 🔍 Project Steps
1. **Load & Explore Data**  
2. **Data Preprocessing**
   - Missing value handling
   - Feature encoding (Label, One-Hot)
   - Feature scaling (StandardScaler)
3. **Model Training**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor (✅ Best)
   - Lasso Regression (optional)
4. **Model Evaluation**
   - MAE, MSE, RMSE, R² Score

## 🧠 Best Model: Random Forest Regressor
- **MAE**: 0.03  
- **MSE**: 2.66  
- **RMSE**: 1.63  
- **R² Score**: 0.0025

## 💾 Files
- `house_prices.csv` — Dataset  
- `House_price_pred_ML_project.ipynb` — Full notebook  
- `random_forest_regressor_model.pkl` — Saved model  

## 📌 Notes
- This dataset had missing values, mixed types, and required careful preprocessing.
- Model performance is modest — further **feature engineering** like extracting BHK from Title, or grouping locations into zones, can improve it.

## 🛠 Future Work
- Add BHK feature
- Group locations by city zones
- Add custom visualizations

## 📦 Download Dataset and Model

Due to GitHub's file size limits, the dataset and trained model are available separately via Google Drive:

- 📂 **Dataset (CSV)**: [Download house_prices.csv](https://drive.google.com/file/d/1jAEIPt9C_g2w--Tsoz2l2OYj3foiKjtT/view?usp=sharing)
- 🤖 **Trained Random Forest Model (PKL)**: [Download random_forest_regressor_model.pkl](https://drive.google.com/file/d/1GwtooemsBEprr4ziL795eGXj-pR5C91B/view?usp=sharing)

> 💡 After downloading, place both files in the same folder as the notebook to run it without errors.
