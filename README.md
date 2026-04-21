# House Price Prediction Model 
This project implements a **Random Forest Regressor** to predict residential home prices based on architectural and land features.

##  Performance
- **Model:** Random Forest (200 Estimators)
- **Error Metric:** Mean Absolute Error (MAE) of ~$22,218
- **Key Features:** Lot Area, Year Built, 1st Floor SqFt, Full Baths, etc.

##  Requirements
- Python 3.x
- Pandas, Scikit-Learn, NumPy

##  Data Setup
Due to licensing, the dataset is not included. To run this:
1. Download `train.csv` from the [Kaggle House Prices Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).
2. Place it in a folder named `/data` in the project root.
