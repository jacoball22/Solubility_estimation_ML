# Molecular Solubility Prediction 🧪

This repository contains my **first machine learning project**, completed by following a tutorial by **Data Professor**.  
The objective is to build regression models that predict the **aqueous solubility of molecules (logS)** using molecular descriptors.

---

## 📂 Dataset

The project uses the **Delaney Solubility with Descriptors** dataset, which includes molecular properties such as:
- Molecular Weight
- Number of Rotatable Bonds
- Other physicochemical descriptors

---

## 📝 Methodology

1. **Data Splitting**
   - Training set: 80%
   - Test set: 20%

2. **Model Training**
   Two regression models were trained:
   - Linear Regression
   - Random Forest Regressor

3. **Evaluation Metrics**
   Model performance was evaluated using:
   - Mean Squared Error (MSE)
   - Coefficient of Determination (R²)

---

## 📊 Results

The **Random Forest Regressor** achieved better performance on the test set compared to **Linear Regression**.

| Model               | Test MSE | Test R² |
|--------------------|----------|---------|
| Linear Regression  | 1.02     | 0.79    |
| Random Forest      | 0.64     | 0.87    |

---

## 🛠️ Libraries Used

- **Pandas** – data handling and preprocessing  
- **Scikit-learn** – model training and evaluation  
- **NumPy** – numerical computations  
- **Matplotlib** – data visualization  

---

## 📌 Notes

This project served as an introduction to:
- Regression models
- Model evaluation
- Working with real chemical datasets
