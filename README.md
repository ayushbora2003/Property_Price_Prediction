# 🏠 California Housing Price Prediction

## 📌 Project Overview
Predict median house prices in California using regression models. This is a beginner-friendly machine learning project.

## 🎯 Objective
- Build Simple Linear Regression (one feature)
- Build Multiple Linear Regression (multiple features)
- Compare both models
- Understand what affects housing prices

## 🛠️ Installation
```bash
# Clone the repository
git clone https://github.com/ayushbora2003/property_price_prediction.git
cd property-price-prediction

# Install requirements
pip install -r requirements.txt

📊 Dataset
California Housing Dataset from 1990 with features:

    - median_income: Median income in block group

    - housing_median_age: Median age of houses

    - total_rooms: Total number of rooms

    - total_bedrooms: Total number of bedrooms

    - population: Total population in block group

    - households: Total number of households

    - latitude: Latitude coordinate

    - longitude: Longitude coordinate

    - ocean_proximity: Distance from ocean (categorical)

    - Target Variable: median_house_value


📁 Project Structure
text
property-price-prediction/
├── README.md
├── requirements.txt
├── .gitignore
├── notebook/
│   └── Property_Price_Prediction.ipynb
└── data/
    └── housing.csv

#Steps in Notebook
   - Data Loading & Exploration

   - Data Cleaning (handle missing values)

   - Data Visualization (understand patterns)

   - Simple Linear Regression (one feature)

   - Multiple Linear Regression (all features)

   - Model Evaluation (MSE, RMSE, R²)

#Results Comparison

📈 Results
| Model                          | R² Score  | Error  | Performance |
| ------------------------------ | --------- | ------ | ----------- |
| **Multiple Linear Regression** | **0.635** | Lower  | ✅ Better    |
| Simple Linear Regression       | 0.459     | Higher | ❌ Worse     |


		
📚 What I Learned
    - Data preprocessing techniques

    - How to train regression models

    - Model evaluation metrics

#Feature importance analysis

👨‍💻 Author
    ayushbora2003

📝 License
This project is open source.



