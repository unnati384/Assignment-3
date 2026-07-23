# Assignment-
# Salary Prediction using Polynomial Regression

## Objective

The objective of this project is to predict employee salaries based on their position level using Polynomial Regression. Since the relationship between position level and salary is non-linear, Polynomial Regression is used to improve prediction accuracy over Linear Regression.

---

## Dataset

**Position Salaries Dataset**

Kaggle Link:
https://www.kaggle.com/datasets/akram24/position-salaries

> Note: The dataset is not included in this repository. Please download it from the Kaggle link above.

---

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Methodology

1. Loaded the dataset using Pandas.
2. Explored the dataset using `head()`, `info()`, and `describe()`.
3. Checked for missing values.
4. Selected **Level** as the input feature and **Salary** as the target variable.
5. Split the dataset into training (80%) and testing (20%) sets.
6. Applied Polynomial Features with **Degree = 3**.
7. Trained a Polynomial Regression model using Linear Regression.
8. Predicted salaries for the test dataset.
9. Evaluated the model using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
10. Visualized the original data and Polynomial Regression curve.

---

## Results

- Successfully trained a Polynomial Regression model.
- Generated salary predictions for unseen data.
- Evaluated model performance using MAE, MSE, and R² Score.
- Created scatter plot and Polynomial Regression curve for visualization.
- The Polynomial Regression model accurately captured the non-linear relationship between position level and salary.

---

## Conclusion

Polynomial Regression provides a better fit for non-linear datasets than Linear Regression. By introducing polynomial features, the model successfully learned the curved relationship between position level and salary, resulting in more accurate predictions. This approach is well suited for salary estimation problems where the relationship between variables is not linear.

---

## Repository Structure

```
Assignment-3/
│── Assignment-3.ipynb
│── Assignment-3.py
│── README.md
```

---

## Author

**Unnati Gupta**

B.Tech CSE (AI & ML)

VIT Bhopal University
