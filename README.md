# 🚗 Vehicle Curb Weight Prediction using Linear Regression

This project focuses on predicting the **curb weight** of passenger vehicles using **linear regression models**. We explore multiple vehicle attributes like engine size, horsepower, dimensions, and fuel efficiency to develop predictive models based on data from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/).

---

## 📂 Dataset

- **Source**: UCI Machine Learning Repository (Automobile dataset)
- **Format**: CSV
- **Link**: [M2_Data.csv](https://raw.githubusercontent.com/mri177/DS-M2-Assignment/main/M2_Data%20(3).csv)
- **Rows**: 204
- **Features**: 26 attributes including:
  - Vehicle dimensions (length, width, height, wheel-base)
  - Engine characteristics (engine-size, horsepower, peak-rpm)
  - Mileage (city-mpg, highway-mpg)
  - Curb-weight (Target variable)

---

## 🔍 Project Objectives

- Clean and preprocess raw vehicle data.
- Explore data using EDA and identify meaningful patterns.
- Select relevant features based on correlation with curb weight.
- Build and evaluate **two linear regression models** using:
  - Model 1: `engine_size`, `horsepower`, `width`
  - Model 2: `length`, `wheel_base`, `highway_mpg`
- Compare models using **K-Fold Cross Validation (K=5)** and choose the best one.

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn (Linear Regression, Cross-Validation, Evaluation Metrics)
- SciPy (Winsorization)
- Jupyter Notebook

---

## 📈 Results

- **Model 1 (engine_size, horsepower, width)** achieved an **average R² = 0.851**
- **Model 2 (length, wheel_base, highway_mpg)** achieved an **average R² = 0.825**
- ✅ **Model 1** was selected as the **preferred model** for curb weight prediction.

---

## 📌 Key Insights

- Width, engine size, and horsepower are strong predictors of curb weight.
- Proper data preprocessing (handling missing values, scaling, encoding) significantly impacts model performance.
- Visualizing data relationships helps identify the best features for regression modeling.

---

## 📚 Future Enhancements

- Explore non-linear models (e.g., polynomial regression, tree-based models).
- Apply regularization (Ridge/Lasso) for multicollinearity handling.
- Expand dataset or perform feature engineering for improved performance.

---

## 📬 Contact

**Mridul Sankarakumar**  
✉️ msankara@mail.yu.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/mridul-sankarakumar)

---

> ⭐️ If you found this project helpful, feel free to star the repo and connect!
