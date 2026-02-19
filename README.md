# 🚗 Fuel Consumption ML

Predicting vehicle fuel consumption using **Linear Regression** and **Polynomial Regression**.

This project walks through the machine learning workflow: data exploration, preprocessing, model training, evaluation, and interpretation with simple regression models.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `FuelConsumptionCo2.csv` | Original dataset of vehicle fuel consumption and CO₂ emissions |
| `fuel_consumption.ipynb` | Jupyter Notebook with all code, EDA, preprocessing, modeling, and evaluation |
| `README.md` | This file |

---

## 📊 About the Dataset

The dataset includes real vehicle data like:

- Engine size  
- Number of cylinders  
- Transmission type  
- Fuel consumption (city, highway, combined)  
- CO₂ emissions  

We use these features to train regression models to predict **fuel consumption**.

---

## 🧠 What This Project Does

### 1. Exploratory Data Analysis (EDA)

- Visualize distributions of numeric and categorical features  
- Analyze relationships between features and the target  
- Heatmap to see correlations

### 2. Data Preprocessing

- Handle missing values (median imputation for numeric)  
- Encode categorical fields (e.g., transmission, drive)  


### 3. Model Training

Two regression models are trained and evaluated:

- **Linear Regression**
- **Polynomial Regression** (with degree > 1 for non‑linear relationships)

### 4. Evaluation

- **RMSE (Root Mean Squared Error)**
- **R² Score**  
Both models are compared to see which fits the data better.

---

## 🛠 How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/Raya1313/fuel_consumption_ML.git
cd fuel_consumption_ML
