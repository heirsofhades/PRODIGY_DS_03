# PRODIGY_DS_03
Task 03 – Decision Tree Classifier | Prodigy InfoTech
- Bank Marketing Dataset

## 📌 Objective
Build a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on demographic and behavioral data.

---

## 📂 Dataset Information
- **Source:** UCI Machine Learning Repository
- **File:** `bank-full.csv`
- **Records:** 45,211
- **Target column:** `y` (yes/no)

---

## 🧰 Tools & Libraries Used
- Python 3
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (sklearn)

---

## 🔍 Exploratory Data Analysis (EDA)
- Checked for null values
- Viewed dataset structure and shape
- Inspected class balance of the target variable

---

## 🧼 Data Preprocessing
- Label Encoded `y` (`yes` → 1, `no` → 0)
- One-Hot Encoded categorical columns like `job`, `education`, `marital`, etc.
- Train-test split: 80% train, 20% test

---

## 🌳 Model Building – Decision Tree
- Trained a `DecisionTreeClassifier` from `sklearn`
- Used `max_depth=5` to avoid overfitting

---

## 📈 Model Evaluation
- **Accuracy:** ~89.7%
- **Confusion Matrix:**
    ```
               Predicted
               No    Yes
           ---------------
Actual No | 7753   199
Actual Yes|  729   362
    ```
- Model performs well on the majority class (`no`), with some imbalance on class `yes`.

---

## 📊 Tree Visualization
Visualized the trained decision tree using `plot_tree()` with feature names and class labels.

---
---

📢 **LinkedIn Post**

Want to see a quick summary and insights?  
Check out my LinkedIn post here 👉  
🔗 [View on LinkedIn](https://www.linkedin.com/posts/bhavesh-uchainiya-734651136_datascience-machinelearning-decisiontree-activity-7348103437428953088-AROS?utm_source=share&utm_medium=member_desktop&rcm=ACoAACEzB9gB68oVgeCqSHu01XNoWfb_ViJtAeg)

---

## ✅ Conclusion
The decision tree model gives a strong accuracy on this classification task. Further improvements can include:
- Handling class imbalance (e.g., SMOTE, class weights)
- Hyperparameter tuning
- Comparing with other models like Random Forest or Logistic Regression

---
