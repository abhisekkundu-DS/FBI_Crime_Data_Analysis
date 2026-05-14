# FBI Crime Data Analysis

A machine learning project for predicting crime types using XGBoost, Random Forest, and Linear Regression models.

## 📊 Project Overview
This project analyzes FBI crime data and builds predictive models to classify crime types based on temporal and spatial features.

## 📁 Project Structure
```
project/
├── notebooks/
│   └── Model_Building.ipynb          # Main analysis and model training
├── app/
│   └── app.py                        # Streamlit web application for predictions
├── models/
│   ├── xgboost_model.pkl
│   ├── linear_regression.pkl
│   ├── random_forest.pkl
│   ├── scaler.pkl
│   ├── label_encoder.pkl
│   ├── feature_names.pkl
│   └── xgboost_model.json
├── visualizations/                   # Generated plots and charts
├── Data_sets/                        # Training and test data
├── .gitignore
└── README.md
```

## 🔧 Installation

### Requirements
- Python 3.8+
- pip

### Setup
```bash
git clone https://github.com/abhisekkundu-DS/FBI_Crime_Data_Analysis.git
cd FBI_Crime_Data_Analysis
pip install -r requirements.txt
```

## 📈 Model Performance

| Model | MAE | RMSE | R² Score |
|-------|-----|------|----------|
| XGBoost | - | - | - |
| Random Forest | - | - | - |
| Linear Regression | - | - | - |

## 🎯 Features Used
- **Temporal**: Hour, Month, Day, Is_Weekend
- **Spatial**: Latitude, Longitude

## 🚀 Usage

### 1. Run Analysis Notebook
```bash
jupyter notebook notebooks/Model_Building.ipynb
```

### 2. Run Prediction App
```bash
streamlit run app/app.py
```

Then open `http://localhost:8501` in your browser.

## 📊 Key Insights
- Temporal patterns (hour of day) are the strongest predictors
- Geographic location (latitude/longitude) contributes significantly
- XGBoost provides the best predictive performance

## 🔍 Top Features by Importance
1. Hour
2. Latitude
3. Longitude
4. Month
5. Is_Weekend

## 📝 Author
**Abhisek Kundu**
- GitHub: [abhisekkundu-DS](https://github.com/abhisekkundu-DS)

## 📄 License
MIT License - feel free to use this project for educational purposes.