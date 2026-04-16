# 🧠 Feature Selection Techniques in Machine Learning

This project demonstrates three major feature selection techniques:

* 📌 Filter Method
* 📌 Wrapper Method
* 📌 Embedded Method

Using a **Heart Disease dataset**, the project compares how each method selects important features for prediction.

---

## 📂 Project Structure

```bash
├── filter_method.ipynb       # Filter method (statistical techniques)
├── wrapper_method.ipynb      # Wrapper method (model-based selection)
├── embedded_method.ipynb     # Embedded method (regularization)
└── README.md
```

---

## 📌 Project Overview

Feature selection is crucial in machine learning to:

* Improve model performance
* Reduce overfitting
* Decrease training time
* Enhance interpretability

This project explores and compares three approaches to selecting the most relevant features.

---

## 📊 Dataset

* **Dataset:** Heart Disease Dataset
* **Target Variable:** `target` (0 = No disease, 1 = Disease)

### 🔑 Features include:

* age, sex, chest_pain_type
* cholesterol, resting_bp_s
* max_heart_rate, exercise_angina
* oldpeak, st_slope

---

## 🔍 1. Filter Method

* Uses **statistical techniques** to evaluate feature importance
* Independent of any machine learning model

### ✔️ Characteristics:

* Fast and simple
* Does not consider feature interactions

👉 Example techniques:

* Correlation
* Chi-square
* Variance threshold

---

## 🔄 2. Wrapper Method

* Uses a **machine learning model** to evaluate feature subsets
* Selects features based on model performance

### ✔️ Characteristics:

* More accurate than filter method
* Computationally expensive

👉 Example techniques:

* Forward Selection
* Backward Elimination
* Recursive Feature Elimination (RFE)

---

## ⚙️ 3. Embedded Method

* Performs feature selection **during model training**

### ✔️ Techniques Used:

#### 🔹 L1 Regularization (LASSO)

* Removes less important features (coefficients → 0)

#### 🔹 L2 Regularization (Ridge)

* Assigns importance weights to all features

---

## 📈 Key Insights

* 📌 Filter method is fastest but less accurate
* 📌 Wrapper method gives better performance but is slower
* 📌 Embedded method provides a balance between speed and accuracy
* 📌 LASSO helps reduce feature count effectively
* 📌 Ridge helps rank feature importance

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas
* Scikit-learn
* NumPy

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/feature-selection-project.git
cd feature-selection-project
```

2. Install dependencies:

```bash
pip install pandas numpy scikit-learn
```

3. Run notebooks:

```bash
jupyter notebook
```

---

## 📌 Future Improvements

* Compare model accuracy across methods
* Add visualization of feature importance
* Apply on multiple datasets
* Combine methods for hybrid feature selection

---

## 📬 Conclusion

This project provides a clear comparison of **Filter, Wrapper, and Embedded feature selection methods**, helping understand their strengths, limitations, and practical use cases in machine learning.

---
