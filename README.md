# Task5_ElevateLabs
# Decision Trees & Random Forest — Heart Disease Prediction

## 📌 Objective

The objective of this task is to understand and implement **tree-based machine learning models** for classification.
We trained a Decision Tree and Random Forest model to predict the presence of heart disease and analyzed overfitting and model performance.

---

## 🛠 Tools & Libraries Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Dataset

Heart Disease Dataset (CSV)

The dataset contains patient medical information such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Maximum Heart Rate
* Exercise Induced Angina
* ST Depression
* Target (0 = No Disease, 1 = Disease)

---

## 🔎 Steps Performed

### 1. Data Loading

* Uploaded dataset into Google Colab
* Loaded using Pandas

### 2. Data Cleaning

* Removed duplicate rows to prevent data leakage

### 3. Train-Test Split

* Applied stratified 80-20 split to maintain class balance

---

## 🌳 Decision Tree Model

* Trained full decision tree
* Visualized tree structure
* Observed overfitting behavior

### Overfitting Control

* Limited tree depth (pruning)
* Compared performance before and after pruning

---

## 🌲 Random Forest Model

* Trained ensemble model using multiple trees
* Compared performance with Decision Tree

---

## 📊 Results

| Model         | Accuracy |
| ------------- | -------- |
| Decision Tree | ~77%     |
| Pruned Tree   | ~80%     |
| Random Forest | ~77%     |

---

## 📈 Feature Importance

Random Forest was used to identify the most influential features affecting heart disease prediction.

---

## 🔁 Cross Validation

Applied 5-fold cross-validation to evaluate model generalization.

---

## 🧠 Interview Questions

**1. How does a decision tree work?**
It splits data based on feature conditions to maximize class separation.

**2. Entropy & Information Gain**
Measures impurity reduction after a split.

**3. Why Random Forest is better?**
It combines multiple trees to reduce overfitting.

**4. Overfitting Prevention**
Limit depth, pruning, or use ensemble models.

**5. What is Bagging?**
Training multiple models on random samples and averaging results.

**6. Tree Visualization**
Using plot_tree or Graphviz.

**7. Feature Importance**
Shows which features most influence predictions.

**8. Pros/Cons of Random Forest**
High accuracy but less interpretable.

---

## 🏁 Conclusion

The pruned decision tree performed better than the full tree, demonstrating that controlling model complexity reduces overfitting. Random Forest did not significantly outperform due to the small dataset size, showing that ensemble models require sufficient data diversity for maximum effectiveness.

---

## 👨‍💻 Author

Mohd Yusuf Khan
