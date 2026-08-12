# 🌲 Intuition of Random Forest

A comprehensive collection of notebooks that explain the **core intuition behind Random Forest** from scratch. This project focuses on understanding how Random Forest builds multiple decision trees using different sampling techniques and combines them to improve prediction accuracy.

> 📚 Perfect for beginners who want to understand *why* Random Forest works before using machine learning libraries.

---

## 📖 Overview

Random Forest is one of the most powerful **ensemble learning** algorithms used for both **classification** and **regression** problems.

Instead of relying on a single decision tree, Random Forest creates **multiple trees**, each trained on different subsets of the data and features. The final prediction is obtained by combining the predictions of all trees.

This repository explains the intuition behind Random Forest through separate notebooks.

---

## 📂 Project Structure

```
Intuition-Of-RandomForest/
│
├── Using-Row-Sampling/
│   └── Demonstrates Bootstrap Sampling
│
├── Using-Feature-Sampling/
│   └── Explains Random Feature Selection
│
├── Using-Combined-sampling/
│   └── Combines Row + Feature Sampling
│
└── README.md
```

---

## 🎯 Topics Covered

### ✅ Row Sampling (Bootstrap Sampling)

- Random selection of training samples
- Sampling with replacement
- Out-of-Bag (OOB) samples
- Creating diverse decision trees

---

### ✅ Feature Sampling

- Random feature selection at every split
- Reducing correlation among trees
- Improving model diversity
- Preventing overfitting

---

### ✅ Combined Sampling

- Bootstrap Sampling
- Random Feature Selection
- Building multiple independent trees
- Majority Voting

---

## 🌳 How Random Forest Works

1. Select random samples from the dataset (Bootstrap Sampling).
2. Train a Decision Tree on each sampled dataset.
3. At every split, randomly choose a subset of features.
4. Grow each tree independently.
5. Repeat for multiple trees.
6. Combine all predictions using:

- **Majority Voting** (Classification)
- **Average Prediction** (Regression)

---

## 📊 Why Random Forest Performs Better

- Reduces overfitting
- Low variance
- Handles missing values
- Works well on large datasets
- Robust against noisy data
- Better generalization than a single Decision Tree

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## ▶️ Getting Started

### Clone Repository

```bash
git clone https://github.com/harshbhatt15/Demo_Codes.git
```

### Navigate to the Project

```bash
cd Demo_Codes/Intuition-Of-RandomForest
```

### Install Dependencies

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open any notebook to explore the concepts step-by-step.

---

## 📚 Key Concepts Explained

- Decision Trees
- Ensemble Learning
- Bagging
- Bootstrap Sampling
- Random Feature Selection
- Majority Voting
- Out-of-Bag (OOB) Error
- Bias-Variance Tradeoff

---

## 📈 Advantages of Random Forest

- High prediction accuracy
- Handles high-dimensional datasets
- Less prone to overfitting
- Works for both Classification and Regression
- Feature Importance estimation
- Robust to outliers and noise

---

## ⚠️ Limitations

- Slower than a single Decision Tree
- Higher memory usage
- Less interpretable
- Longer training time for very large datasets

---

## 🎓 Learning Outcomes

After completing this project, you will understand:

- How Bootstrap Sampling works
- Why Feature Sampling is important
- Why Random Forest reduces overfitting
- Difference between Decision Tree and Random Forest
- Bagging intuition
- Ensemble Learning concepts
- Real-world applications of Random Forest

---

## 🚀 Applications

- Fraud Detection
- Medical Diagnosis
- Credit Risk Analysis
- Customer Churn Prediction
- Spam Detection
- Stock Market Prediction
- Recommendation Systems

---

## 📖 References

- Breiman, L. (2001). *Random Forests.*
- Random Forest combines bootstrap sampling and random feature selection to create diverse decision trees whose aggregated predictions improve accuracy and reduce overfitting. :contentReference[oaicite:0]{index=0}

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create a new feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

---

## 👨‍💻 Author

**Harsh Bhatt**

