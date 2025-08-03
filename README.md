# PRODIGY_TrackCode_03

# 💼 Task 3: Decision Tree Classifier – Bank Marketing Dataset

**Track**: Data Science Internship  
**Task**: Build a Decision Tree classifier to predict whether a customer will subscribe to a term deposit (purchase a product), using the UCI Bank Marketing Dataset.  

---

## 📁 Dataset Used

**Source**: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)  
**File**: `bank.csv`  
**Target Column**: `y` (binary: "yes" or "no")

---

## 🧠 Objective

To develop a machine learning model using a **Decision Tree Classifier** that can classify whether a customer will **subscribe to a term deposit** based on demographic and behavioral features.

---

## 🔧 Technologies & Libraries

- Python 🐍
- Pandas
- NumPy
- scikit-learn
- Graphviz
- Matplotlib

---

## 🚀 Workflow

1. **Data Loading**
   - Loaded `bank.csv` with `;` separator.
2. **Preprocessing**
   - One-hot encoding for categorical variables.
   - Label encoding for the target variable `y`.
3. **Model Training**
   - Split data into training & testing sets.
   - Trained a `DecisionTreeClassifier` from `sklearn.tree`.
4. **Model Evaluation**
   - Printed classification report and accuracy score.
5. **Visualization**
   - Rendered a clear Decision Tree using Graphviz.

---

## 📊 Output

- ✅ **Classification Report**  
- ✅ **Accuracy Score**  
- ✅ **Decision Tree Visualization**

> You can find the tree plot in `tree_visualization.png` if exported.

---


## 📌 Folder Structure

