# 📊 Food Insecurity Prediction in U.S. Communities

This project uses machine learning techniques to analyze and predict food insecurity trends in the United States based on demographic and socioeconomic data. It covers both regression and binary classification tasks, evaluates multiple ML models, and explores fairness-aware metrics.

---

## 📁 Project Structure

- `Food_Insecurity_Modeling_Notebook.ipynb`: Main Jupyter notebook for data preparation, modeling, and evaluation.
- Combined Excel dataset (uploaded by user during notebook execution).
- Final model evaluation includes regression and classification summaries and visualizations.

---

## 📌 Problem Statement

The goal is to predict food insecurity in U.S. communities and classify areas into high/low risk using historical features such as:
- Food insecurity rates by race, age, and household type
- Total number of food-insecure individuals by demographic
- Yearly records (2019–2023)

---

## 🧪 ML Tasks

### 🟢 **Regression**
Predict the overall food insecurity rate (continuous output).

### 🔵 **Classification**
Classify areas into `'High'` or `'Low'` food insecurity based on a threshold rate (>9%).

---

## 🧠 Models Used

### ✅ Regression Models:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- KNN Regressor
- SVR

### ✅ Classification Models:
- Decision Tree Classifier
- Random Forest Classifier
- KNN Classifier  
*Logistic Regression and SVM were skipped due to class imbalance.*

---

## 📈 Evaluation Metrics

### 📉 Regression:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 📊 Classification:
- Accuracy
- Precision
- Recall
- F1 Score

Visual comparison is provided through bar plots for F1 and MAE.

---

## ⚖️ Fairness Metrics (Theoretical)
The project introduces:
- **Disparate Impact Ratio**
- **Equal Opportunity Difference**

These metrics are explained and intended for future implementation with more granular, group-based datasets.

---

## 🚀 How to Use

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload the combined Excel dataset when prompted.
3. Run each cell step-by-step for:
   - Data preparation
   - Model training & evaluation
   - Performance visualization

---

## ✅ Requirements

All required libraries are imported and installed automatically within the Colab notebook:
- `pandas`, `numpy`, `seaborn`, `matplotlib`
- `sklearn` (for preprocessing, models, and metrics)

---

## 📌 Recommendations for Future Work

- Use county-level data to improve model granularity
- Perform explicit fairness testing across demographic groups
- Address classification imbalance using rebalancing techniques like SMOTE

---

## 📜 License

This project is developed for academic and educational purposes. Attribution is appreciated if reused.

---
