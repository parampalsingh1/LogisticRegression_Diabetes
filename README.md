# 🩺 Logistic Regression - Diabetes Prediction
A logistic regression model implemented **from scratch** to predict diabetes using the **Pima Indians Diabetes dataset**.

## 📌 Project Overview
This project implements **logistic regression from scratch** using NumPy to classify whether a patient has diabetes. The goal is to **understand the fundamentals** of logistic regression, including:

- **Data preprocessing**: Handling missing values, feature scaling, and data splitting.
- **Training a custom gradient descent optimizer** for parameter optimization.
- **Implementing logistic regression probability function** and loss calculation.
- **Evaluating model performance** using accuracy, precision, recall, F1-score, and AUC-ROC.
- **Comparing performance** with **scikit-learn’s Logistic Regression model**.
- **Visualizing training** by plotting the loss function over iterations.

---

## 📊 **Model Performance Comparison**
| Metric        | Custom Model | Scikit-Learn |
|--------------|-------------|--------------|
| **Accuracy**  | 76.62%      | 77.27%       |
| **Precision** | 72.73%      | 74.36%       |
| **Recall**    | 58.18%      | 52.73%       |
| **F1 Score**  | 64.65%      | 61.70%       |
| **AUC-ROC**   | 0.8389      | 0.8505       |

🔹 The **custom model closely matches scikit-learn’s results**, proving the effectiveness of manual gradient descent implementation.

---

## 🔬 **Insights & Findings**
- **Both models perform similarly**, indicating that a manually implemented logistic regression model can be practical.
- **Custom implementation provides transparency** into the model's workings, making it useful for research and educational purposes.
- **Scikit-learn’s model is more optimized and robust** for general use cases.

---

## 📜 **Key Learnings**
✔ Understanding logistic regression from first principles.
✔ Implementing gradient descent for parameter tuning.
✔ Handling missing data and normalizing features.
✔ Evaluating classification models using multiple metrics.
✔ Comparing custom implementation with scikit-learn.

---

## 📜 **License**
This project is licensed under the **MIT License**.

