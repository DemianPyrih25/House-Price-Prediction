# House Price Prediction

A machine learning project to predict house prices based on various features.

## Dataset

**Source:** Kaggle - Housing Prices Dataset  
**Link:** https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

**Alternative datasets:**
- https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction
- https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

### Dataset Description
The dataset contains information about houses with features like:
- Area (square feet)
- Number of bedrooms
- Number of bathrooms
- Number of stories
- Parking spaces
- Amenities (mainroad, guestroom, basement, etc.)
- Price (target variable)

## Installation

1. Install required libraries:
```bash
pip install -r requirements.txt
```

2. Download the dataset from Kaggle and place it in the project directory

3. Open the Jupyter notebook:
```bash
jupyter notebook House_Price_Prediction.ipynb
```

## Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

## Results

- R² Score: ~0.95+
- RMSE: Low prediction error
- Key features: Area and bedrooms are most important

## How to Download Dataset from Kaggle

1. Go to https://www.kaggle.com/datasets/yasserh/housing-prices-dataset
2. Click "Download" button
3. Extract the CSV file
4. Place it in the project folder
