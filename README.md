# CodeAlpha_task3

This project develops a machine learning model to predict the selling price of used cars based on various features. The dataset contains information such as car brand, present price, kilometers driven, fuel type, transmission type, and seller type. By applying data preprocessing, feature encoding, and regression models, the project demonstrates how ML can solve real-world pricing problems used in online car marketplaces.


---

# 🚗 Car Price Prediction  


# Car Price Prediction  

## Objective  
Predict **used car prices** based on features like brand, price, kilometers driven, fuel type, and transmission.  

## Workflow  
- Load dataset (`car data.csv`).  
- Drop irrelevant columns (`Car_Name`).  
- Encode categorical features (`Fuel_Type`, `Selling_type`, `Transmission`).  
- Split into features (**X**) and target (**y = Selling_Price**).  
- Train-test split (80-20).  
- Train ML model (**Random Forest Regressor**).  
- Evaluate with **R² Score & MAE**.  
- Visualize **feature importance**.  
- Predict price for new input data.  

## Key Learning  
- End-to-end **regression pipeline**.  
- **Feature engineering & encoding**.  
- Real-world ML in **used car marketplaces**.  

## Libraries Used  
- pandas  
- numpy  
- matplotlib, seaborn  
- scikit-learn  


