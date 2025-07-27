
# California Housing Price Prediction

A machine learning project to predict median house prices in California districts using various regression algorithms. The dataset is based on the 1990 California census and includes housing, population, geographic, and economic features.

---

##  Project Overview

This project walks through an end-to-end ML pipeline to:

- Understand and preprocess the data
- Explore key correlations and distributions
- Train multiple regression models
- Evaluate and compare their performance

---

##  Dataset Features

- Median Income
- House Age
- Average Rooms
- Population
- Latitude & Longitude
- Proximity to Ocean (Categorical)
- Median House Value (Target)

Dataset Source: [StatLib - California Housing](https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html)

---

##  Models Used

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Support Vector Machine (SVM)  
- XGBoost Regressor  

---

##  Performance Comparison

| Model               | R² Score | RMSE   | MSE   |
|---------------------|----------|--------|--------|
| Linear Regression   | 0.6286   | 0.6070 | 0.3684 |
| Decision Tree       | 0.6304   | 0.6056 | 0.3667 |
| Random Forest       | 0.8083   | 0.4361 | 0.1902 |
| SVM                 | 0.7590   | 0.4890 | 0.2391 |
| XGBoost             | **0.8193** | **0.4234** | **0.1793** |

---

##  Conclusion

Among all models tested, **XGBoost Regressor** achieved the best performance with an **R² score of 0.8193** and the **lowest RMSE (0.4234)**. This indicates XGBoost captures complex patterns in the data better than other models, making it the most suitable for real-world deployment in housing price prediction.

---

##  Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  
- Jupyter Notebook  

---

##  Future Enhancements

- Hyperparameter tuning for all models  
- Use cross-validation for better generalization  
- Add external features (crime rate, schools, etc.)  
- Build an interactive web app using Flask or Streamlit

---



