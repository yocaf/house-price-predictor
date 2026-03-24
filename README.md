# 🏠 House Price Predictor

A machine learning model that predicts house sale prices using the Ames Housing dataset.

## 🏆 Results
- **Model**: XGBoost
- **R²**: 0.9131
- **Average Price Error**: $14,018
- **Kaggle Score**: 0.12804 (top 20% globally)

## Tech Stack
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Jupyter Notebook
- Git, GitHub, Kaggle

## What I Did
- Cleaned 19 columns with missing values
- Engineered new features: TotalSF, TotalBath, HouseAge, IsRemodeled
- Ordinal encoded 10 quality columns
- Target encoded Neighborhood
- Tuned XGBoost with RandomizedSearchCV
- Submitted to Kaggle competition

## How to Run
```bash
git clone https://github.com/yocaf/house-price-predictor.git
cd house-price-predictor
python -m venv env
source env/bin/activate
pip install -r requirements.txt
jupyter notebook
```

## What I Learned
- Handling complex missing values (absence vs random missing)
- Feature engineering for tabular data
- Difference between ordinal, target and one-hot encoding
- Model tuning with RandomizedSearchCV
- Submitting to Kaggle competitions
