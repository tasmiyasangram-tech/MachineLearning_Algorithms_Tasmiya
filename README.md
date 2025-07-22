# MachineLearning_Algorithms_Tasmiya
Python scripts implementing five machine learning algorithms
# Machine Learning Model Comparisons

This repository contains implementations of various machine learning models applied to standard datasets using *scikit-learn* and *Seaborn*.

## 🔧 Technologies Used

- Python
- Scikit-learn
- Seaborn
- Pandas
- NumPy (implicitly via scikit-learn)

---

## 📁 Project Structure

### 1. 🎯 Decision Tree on Titanic Dataset
- *Dataset*: Titanic (from Seaborn)
- *Features used*: pclass, sex, age
- *Target*: survived
- *Preprocessing*:
  - Dropped rows with missing values
  - Converted sex column to binary (0 = male, 1 = female)
- *Model*: DecisionTreeClassifier
- *Metric*: Accuracy

---

### 2. 🌸 Logistic Regression on Iris Dataset
- *Dataset*: Iris (from sklearn.datasets)
- *Features*: All 4 features (sepal/petal length & width)
- *Target*: Species classification
- *Model*: LogisticRegression
- *Metric*: Accuracy

---

### 3. 🍷 Random Forest on Wine Dataset
- *Dataset*: Wine (from sklearn.datasets)
- *Features*: All chemical properties
- *Target*: Wine class (0, 1, 2)
- *Model*: RandomForestClassifier
- *Metric*: Accuracy

---

### 4. 🔢 K-Nearest Neighbors on Digits Dataset
- *Dataset*: Digits (from sklearn.datasets)
- *Features*: Flattened 8x8 image pixels
- *Target*: Digit (0–9)
- *Model*: KNeighborsClassifier
- *Metric*: Accuracy

---

output
Accuracy: 0.76  # Titanic - Decision Tree
Accuracy: 0.97  # Iris - Logistic Regression
Accuracy: 0.94  # Wine - Random Forest
Accuracy: 0.98  # Digits - KNN
