# 🚢 Titanic Survival Prediction - Linear Regression (Internship Task 3)

## 📌 Task Overview
In this internship task, we explored the application of **Linear Regression** on the Titanic dataset to predict survival outcomes based on various features. This involved data preprocessing, training a regression model, evaluating its performance, and visualizing results.

---

## ✅ What I Did Today

### 1. 📥 Imported and Preprocessed Dataset
- Loaded Titanic dataset.
- Handled missing values and encoded categorical variables (like `Sex`, `Embarked`, `Pclass`, `Title`).
- Selected features and target:
  - **Features**: `Fare`, `Age`, encoded `Sex`, `Pclass`, `Title`, etc.
  - **Target**: `Survived`

### 2. 🔀 Split Data
- Used `train_test_split` from `sklearn.model_selection` to divide data:
  - `80%` for training
  - `20%` for testing

### 3. 🤖 Trained Linear Regression Model
- Applied `LinearRegression()` from `sklearn.linear_model`.
- Trained model using:

python```
model.fit(X_train, y_train)
y_pred = model.predict(X_test)
print(y_pred)
### 4.Evaluated the  model performance and visualize the linear regression line for feature 'fare'
