## Uber Trip Analysis & Demand Forecasting

Built an end-to-end machine learning project to analyze Uber trip demand and improve forecasting accuracy using ensemble models.

---

##  Project Overview

This project analyzes Uber trip data to uncover demand patterns and build machine learning models to predict ride demand. The objective is to help optimize driver allocation, reduce idle time, and support data-driven decision-making.

---

##  Dataset

- **Dataset:** Uber Trip Data (Jan–Feb)
- **Features include:**
  - Date
  - Active Vehicles
  - Trips
  - Dispatching Base Number

---

##  Tools & Technologies

- **Python:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:**
  - Random Forest
  - Gradient Boosting
  - XGBoost
- **Model Explainability:** SHAP
- **Evaluation Metrics:** RMSE, R² Score

---

##  Key Highlights

- Built a complete ML pipeline (EDA → Feature Engineering → Modeling → Evaluation)
- Implemented ensemble learning to improve prediction accuracy
- Used SHAP for feature importance and model explainability

---

## Exploratory Data Analysis (EDA)

- Analyzed daily trip demand trends
- Compared weekday vs weekend ride patterns
- Studied relationship between trips and active vehicles
- Identified top-performing dispatching bases

---

##  Feature Engineering

- **Extracted:**
  - Day, Month, Weekday
- **Created:**
  - Weekend flag
  - Lag features (lag1, lag7)
  - Rolling average (7-day)

---

##  Machine Learning Models

- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- Ensemble Model (weighted averaging based on performance)

---

##  Model Performance

| Model              | RMSE   | R² Score |
|-------------------|--------|----------|
| Random Forest      | 1326.81 | 0.98     |
| Gradient Boosting  | 1439.54 | 0.98     |
| XGBoost            | 1659.46 | 0.97     |
| Ensemble Model     | 1356.07 | 0.98     |

---

##  Visualizations

- Trips trend over time
- Trips vs Active Vehicles
- Weekday vs Weekend analysis
- Actual vs Predicted comparison
- Residual error analysis
- SHAP feature importance plots

---

##  Key Insights

- Demand is higher on weekends
- Strong correlation between active vehicles and trips
- Certain dispatch bases handle majority of trips
- **Random Forest achieved the best performance with highest accuracy and lowest error**
- Ensemble model provided balanced performance across models

---

##  Business Impact

- Enables accurate demand forecasting
- Improves driver allocation strategy
- Reduces idle time and operational inefficiencies
- Supports better decision-making using data insights

---

##  How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost shap
```
1. Download dataset  
2. Update file path in notebook  
3. Run the notebook  

---

## Project Structure

Uber-Trip-Analysis/
│
├── uber_trip_analysis.ipynb
├── uber_clean.csv
├── README.md

---

## Author

Ankita Arvind Palande
Aspiring Data Analyst
