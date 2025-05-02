# 🌸 Task 6: K-Nearest Neighbors (KNN) Classification 🌸

This project is a part of the **AI & ML Internship** and demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm using the **Iris dataset** from Scikit-learn.

---

## 📌 Objective

To understand and implement the KNN algorithm for a classification problem, evaluate its performance, and visualize the decision boundaries.

---

## 🛠️ Tools & Libraries Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 📊 Dataset

We used the **Iris dataset**, a classic multiclass classification dataset which includes:
- 150 samples
- 4 features per sample (sepal length, sepal width, petal length, petal width)
- 3 target classes (Setosa, Versicolour, Virginica)

---

## 🔍 Steps Performed

1. **Loaded the Iris dataset**
2. **Normalized** features using `StandardScaler`
3. **Split** the data into training and testing sets
4. Trained **KNN Classifier** using different `K` values (1–10)
5. **Evaluated** the model using accuracy and confusion matrix
6. **Visualized** accuracy vs K
7. **Plotted** decision boundaries using 2 features

---

## 🧪 Best K Value

After testing different values of K from 1 to 10, the best value was:

```text
✅ Best K: 3 (Accuracy: 1.00)
