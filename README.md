# Car-Price-Prediction-using-Regression-Models

#  Car Price Prediction using Regression Models

##  Project Overview
This project analyzes a dataset of used cars to **predict selling prices** using different regression techniques.  
We compare multiple models including **Linear Regression, Lasso, Ridge, and Polynomial Regression** to determine which performs best.  

The dataset includes details such as:
- Year of manufacture  
- Mileage (km driven)  
- Fuel type  
- Transmission  
- Car brand  
- Selling price (target variable)  

---

##  Models Implemented
1. **Linear Regression**  
   - Baseline model.  
   - Easy to interpret but struggles with correlated features.  

2. **Lasso Regression**  
   - Performs **feature selection** by shrinking less important coefficients to zero.  
   - Useful when dataset has many irrelevant features.  

3. **Ridge Regression**  
   - Handles **multicollinearity** by shrinking coefficients without eliminating features.  
   - More stable and robust than Linear and Lasso.  
   - **Best performing model in our tests**.  

4. **Polynomial Regression**  
   - Captures **nonlinear relationships** between features and target.  
   - Improved performance in some cases but prone to **overfitting**.  

---

##  Evaluation Metrics
We used the following metrics to compare models:
- **R² Score** → Explains how much variance in target is explained by the model. Higher is better.  
- **Mean Squared Error (MSE)** → Measures prediction error. Lower is better.  

---

##  Key Findings
- **Linear Regression**: Simple but not robust.  
- **Lasso Regression**: Similar to Linear but removed some less important features.  
- **Ridge Regression**: Best balance between bias and variance.  
- **Polynomial Regression**: Sometimes improved accuracy but at risk of overfitting.  

 **Ridge Regression with tuned alpha was the most reliable model.**

---

##  Visualizations
The project includes visualizations for:
- Histogram of selling prices  
- Scatter plot of car age vs price  
- Correlation heatmap of numerical features  
- Predicted vs Actual price plots for model evaluation  

---

##  Next Steps
To further improve predictions:
1. Feature Engineering (e.g., depreciation rate, brand popularity).  
2. Hyperparameter tuning with **GridSearchCV**.  
3. Try advanced models like **Random Forest** or **XGBoost**.  
4. Use **cross-validation** for robust evaluation.  

---

##  Tech Stack
- Python   
- Pandas, NumPy for data processing  
- Matplotlib, Seaborn for visualization  
- Scikit-learn for regression models  

---


##  Conclusion
This project shows how different regression models perform on a real-world dataset.  
While **Polynomial Regression** can capture nonlinearity, **Ridge Regression** was the most balanced and reliable choice.  

 Future work: Explore **tree-based models** for better accuracy.  

---
```



