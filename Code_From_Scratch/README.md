# 🚀 AdaBoost Algorithm from Scratch

A beginner-friendly implementation of the **AdaBoost (Adaptive Boosting)** algorithm built completely from scratch using Python. This project demonstrates the mathematical intuition and working mechanism of AdaBoost without relying on Scikit-learn's built-in `AdaBoostClassifier`.

## 📌 Overview

AdaBoost is an **ensemble learning algorithm** that combines multiple weak learners to create a strong classifier. During each iteration, it assigns higher importance to incorrectly classified samples, allowing subsequent weak learners to focus on harder examples.

This repository is intended for students and machine learning enthusiasts who want to understand the internal workings of AdaBoost.

---

## 🎯 Features

- ✅ Pure Python implementation
- ✅ No built-in AdaBoost implementation used
- ✅ Step-by-step implementation
- ✅ Easy to understand code
- ✅ Educational project for Machine Learning beginners

---

## 🧠 Algorithm Workflow

1. Initialize equal weights for all training samples.
2. Train a weak learner (Decision Stump).
3. Calculate weighted classification error.
4. Compute learner weight (Alpha).
5. Increase weights of misclassified samples.
6. Normalize sample weights.
7. Repeat for multiple iterations.
8. Combine all weak learners using weighted voting.

---

## 📂 Project Structure

```
Adaboost-algorithm/
│
├── adaboost.py          # AdaBoost implementation
├── decision_stump.py    # Weak learner
├── dataset.csv          # Sample dataset (if included)
├── notebook.ipynb       # Jupyter Notebook
└── README.md
```

*(Project structure may vary depending on your files.)*

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn (only for dataset loading/evaluation if used)

---

## 📈 How AdaBoost Works

Unlike Bagging, AdaBoost trains models **sequentially**.

- Initially every sample has equal weight.
- Incorrectly classified samples receive higher weights.
- Correctly classified samples receive lower weights.
- New weak learners focus more on difficult samples.
- Final prediction is obtained using weighted voting of all weak learners.

---

## ▶️ Getting Started

### Clone Repository

```bash
git clone https://github.com/harshbhatt15/Demo_Codes.git
```

```bash
cd Demo_Codes/Code_From_Scratch/Adaboost-algorithm
```

### Install Dependencies

```bash
pip install numpy pandas matplotlib scikit-learn
```

### Run

```bash
python adaboost.py
```

or open the Jupyter Notebook.

---

## 📚 Mathematical Formula

Weighted Error:

\[
Error = \sum w_i \cdot I(y_i \neq \hat{y_i})
\]

Classifier Weight:

\[
\alpha = \frac{1}{2}\ln\left(\frac{1-error}{error}\right)
\]

Weight Update:

\[
w_i = w_i \times e^{-\alpha y_i h_i(x)}
\]

Finally, normalize the weights before the next iteration.

---

## 📊 Applications

- Face Detection
- Spam Detection
- Fraud Detection
- Medical Diagnosis
- Credit Risk Prediction
- Customer Churn Prediction

---

## 🎓 Learning Outcomes

By completing this project, you will understand:

- Ensemble Learning
- Boosting vs Bagging
- Decision Stumps
- Sample Weight Updates
- Weighted Voting
- AdaBoost Mathematics
- Binary Classification

---

## 📖 References

- Freund, Y., & Schapire, R. (1997). *A Decision-Theoretic Generalization of On-Line Learning and an Application to Boosting.*
- AdaBoost builds a strong classifier by iteratively training weak learners and increasing the emphasis on previously misclassified examples.:contentReference[oaicite:0]{index=0}

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a Pull Request

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!

---

## 👨‍💻 Author

**Harsh Bhatt**

GitHub: https://github.com/harshbhatt15

Passionate about Machine Learning, Deep Learning, and Artificial Intelligence.