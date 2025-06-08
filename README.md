# Multivariate Linear Regression

This project implements multivariate linear regression from scratch in Python using NumPy. It predicts the **Chance of Admission** for students based on features like **GRE Score**, **TOEFL Score**, and **CGPA** using gradient descent optimization.

## 📂 Dataset
- **Source**: `Admission_Predict_Ver1.1.csv`
- **Target Variable**: `Chance of Admit`
- **Features**: 
  - GRE Score
  - TOEFL Score
  - CGPA

## 🛠 Features Implemented
- Data normalization
- Hypothesis and cost function
- Gradient descent-based training
- Learning curve visualization
- Model evaluation with R² score and MSE

## 📈 Outputs
- Final learned weights (θ)
- Training cost over iterations
- Actual vs predicted outcomes plot

## 📊 Performance
- **R² Score** and **Mean Squared Error** are calculated on the test set to evaluate the model.

## 📦 Dependencies
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

## 🧠 Purpose
Educational demonstration of implementing linear regression without using ML libraries like `scikit-learn`.

---