# 🚗 Fuel Consumption ML

A machine learning project for analyzing and predicting vehicle fuel consumption using the *Fuel Consumption CO2* dataset.  

This repository includes data exploration, preprocessing, modeling, and evaluation of regression models to predict fuel consumption based on vehicle properties.

---

## 📁 Project Contents

| File | Description |
|------|-------------|
| `FuelConsumptionCo2.csv` | The raw dataset of vehicle fuel consumption and emissions |
| `fuel_consumption.ipynb` | Jupyter Notebook with EDA, preprocessing, and modeling code |
| `README.md` | Project overview and instructions (this file) |

---

## 📊 Dataset Overview

The dataset contains information related to fuel consumption and carbon emissions for various vehicle models, including features such as:

- Model year  
- Engine size  
- Number of cylinders  
- Fuel consumption (city, highway, combined)  
- CO2 emissions  
- Transmission and drive type  

This dataset allows us to explore how different vehicle characteristics affect fuel usage and emissions. :contentReference[oaicite:0]{index=0}

---

## 🧠 What You’ll Find Here

This project demonstrates:

1. **Exploratory Data Analysis (EDA)**  
   - Feature distributions  
   - Correlation analysis  
   - Visualizations to understand relationships between variables.

2. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical features
   - Feature scaling (StandardScaler)

3. **Model Training & Evaluation**
   - Regression modeling for fuel consumption prediction
   - Model performance metrics such as RMSE and R²
   - Comparison of different regression models

4. **Insights and Conclusions**
   - Which features most influence fuel consumption  
   - Model accuracy and limitations

---

## 🛠 Dependencies

Before you run the project, install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
