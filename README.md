# 🤖 Smartphone Purchase Prediction – Capstone Project 📱

This capstone project aims to predict whether a customer will buy a new smartphone using classification machine learning models. The entire workflow includes data analysis, preprocessing, model training, SMOTE balancing, and evaluation.

---

## 🎯 Objective

Build a classification model to predict:

> Will a customer purchase a new smartphone?  
> ✅ Yes = 1  
> ❌ No = 0

---

## 📂 Dataset Features

| Feature               | Description                                         |
|-----------------------|-----------------------------------------------------|
| 🧓 `age`              | Age of the person (in years)                        |
| 💰 `income`           | Monthly income in ₹ (INR)                           |
| ⏱️ `time_on_website`  | Minutes spent on smartphone-related sites           |
| 🛒 `previous_purchases`| Number of past purchases (phones/accessories)      |
| 📱 `target`           | 1 = Will buy a smartphone, 0 = Will not             |

---

## 🧩 Project Workflow

### ✅ Step 1: Data Collection
- Gathered dataset with >1000 records (India + Japan customers)

### ✅ Step 2: Data Preprocessing
- Checked for nulls, data types, encoded if required

### ✅ Step 3: EDA (Exploratory Data Analysis)
- Distribution plots, heatmap, target class check

### ✅ Step 4: Train-Test Split
- 80% training, 20% testing

### ✅ Step 5: Imbalance Handling
- Applied **SMOTE** to oversample minority class

### ✅ Step 6: Model Building
- Tested Logistic Regression, Decision Tree, Random Forest, XGBoost

### ✅ Step 7: Evaluation Metrics
- Accuracy, Precision, Recall, F1-Score, Confusion Matrix

### ✅ Step 8: Best Model
- **XGBoost with SMOTE** performed best:
  - ✅ Accuracy: 91%
  - ✅ Precision (class 1): 0.88
  - ✅ Recall (class 1): 0.94
  - ✅ F1-score: 0.91

### ✅ Step 9: Insights
- Time on website and income were strong predictors  
- Helps target marketing to potential buyers

---

## 🛠️ Tools & Libraries Used

- `Python` 🐍  
- `Pandas`, `NumPy` 📊  
- `Matplotlib`, `Seaborn` 📈  
- `Scikit-learn`, `XGBoost` 🤖  
- `imblearn (SMOTE)` ⚖️  
- `Jupyter Notebook`

---

## 🚀 Future Enhancements

- Add live data pipeline or real-time prediction  
- Model deployment using Flask or Streamlit  
- Interactive dashboard for business decision makers

---


---

## 🧠 What I Learned

- End-to-end classification workflow  
- Handling class imbalance with SMOTE  
- Comparing and tuning multiple ML models  
- Turning raw data into business insight

---

## 📌 Author

**Mandar Kajbaje**  
