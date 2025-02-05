# ML Model Builder

## Overview
ML Model Builder is a Streamlit-based web application that allows users to upload datasets, clean data, preprocess features, train regression models with hyperparameter tuning, and test the trained models with new data.

LIVE : https://ml-model-builder-app.streamlit.app/

![](https://github.com/user-attachments/assets/ebd5c106-0293-4033-806f-85cb618d620c)

## Features
- Upload CSV or Excel datasets
- Data cleaning (remove missing values, drop duplicates)
- Feature encoding and scaling
- Train-test split
- Support for multiple regression models:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - ElasticNet Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - XGBoost
  - Support Vector Regression (SVR)
- Hyperparameter tuning for each model
- Model evaluation using R-squared score
- User input testing for predictions
- Save and download trained models and preprocessing objects

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ml-model-builder.git
   cd ml-model-builder
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Upload your dataset and follow the steps to clean, preprocess, train, and evaluate your model.
3. Test the model with new data.
4. Download the trained model and preprocessing objects for future use.

## Dependencies
```bash
streamlit
pandas
joblib
scikit-learn
xgboost
```
Install dependencies using:
```bash
pip install -r requirements.txt
```

## File Structure
```bash
├── app.py                 # Main Streamlit application
├── requirements.txt       # Required dependencies
├── model.pkl              # Trained model (after saving)
├── transformer.pkl        # Saved transformer (if used)
├── scaler.pkl             # Saved scaler (if used)
└── README.md              # Project documentation
```

## Contributing
Feel free to fork the repository, make changes, and submit pull requests.

