# PRICE-PREDICTOR

This project aims to predict laptop prices using machine learning. A regression model is built to estimate the price based on features like brand, specifications, and other factors.

## Goal
The objective is to develop a model that predicts the price of laptops based on various features like brand, RAM, processor type, and storage.

## Steps Involved
- **Import Libraries**: Load libraries for data manipulation, visualization, and regression modeling.
- **Load Data**: Import the laptop dataset for analysis.
- **Data Visualization**: Explore the dataset to understand relationships between features and prices.
- **Data Preprocessing**: Handle missing values and perform feature engineering.
- **Feature-Label Split**: Separate the features (like RAM, processor) from the target label (price).
- **Normalization**: Standardize features where necessary.
- **Train-Test Split**: Split the data into training and testing sets for model evaluation.
- **Train Model**: Train a regression model (e.g., Linear Regression or Random Forest Regressor).
- **Model Evaluation**: Evaluate the model using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Dataset
The dataset includes various laptop specifications such as brand, RAM, storage, screen size, and other technical details. You can access the dataset via:
`DATASET_LINK = 'https://drive.google.com/file/d/195PLwTu558P8Z8nfbvB5MEbUl5K5Bp7B/view?usp=sharing'`

## Model Details
- **Algorithm**: Regression (e.g., Linear Regression, Random Forest Regressor)
- **Framework**: scikit-learn
- **Features**: Brand, RAM, processor type, storage, screen size, etc.
- **Evaluation**: MAE, MSE, R-squared

## Files
- **Laptop_Price_Predictor.ipynb**: Jupyter notebook containing code for data loading, preprocessing, model training, and evaluation.
- **README.md**: Project documentation, setup instructions, and overview.
