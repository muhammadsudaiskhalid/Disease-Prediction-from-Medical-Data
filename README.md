# 🩺 Disease Prediction from Medical Data

## 📌 Project Overview

This repository contains my **Internship Task** on *Disease Prediction from Medical Data*.
The main objective of this project is to predict the **possibility of diseases** using structured medical datasets and apply multiple **machine learning classification techniques** to evaluate their performance.

I have compared four classification algorithms:

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest
* XGBoost

To make the results more **interactive and easy to understand**, the notebook also includes **visualizations** such as confusion matrices, ROC curves, and accuracy comparison tables.

---

## 🎯 Objectives

* Analyze structured medical data (symptoms, age, test results, etc.).
* Train and evaluate classification models.
* Compare models using **metrics**.
* Present findings in a clear, professional way as part of my **internship work**.

---

## 📂 Datasets

For demonstration, the project uses the **Breast Cancer dataset** (from `sklearn.datasets`).
However, it can easily be extended to:

* **Heart Disease Dataset** (UCI ML Repository)
* **Diabetes Dataset** (UCI ML Repository)

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib, Seaborn
* Scikit-plot

---

## 📊 Results & Visualizations

This project not only prints performance metrics but also **shows visual insights**:

1. **Confusion Matrix (Heatmap)** for each model:

   * Highlights true positives, false positives, true negatives, and false negatives.

2. **ROC Curves**:

   * Compares the tradeoff between sensitivity and specificity for all models.

3. **Accuracy Comparison**:

   * Displays which algorithm performs the best overall.

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/disease_prediction.git  
   cd disease_prediction  
   ```

2. Open the Jupyter Notebook / Google Colab file.

3. Install dependencies (if needed):

   ```bash
   pip install -r requirements.txt  
   ```

4. Run all cells in the notebook.
   You will see:

   * Printed classification reports.
   * Confusion matrices (as heatmaps).
   * ROC curves.
   * Accuracy comparison bar chart.

---

## 📌 Future Work

* Extend to multiple medical datasets (Heart Disease, Diabetes).
* Perform hyperparameter tuning for better accuracy.
* Build a **simple web app** for real-time disease prediction.

---

## 📜 License

This project is for **educational and internship purposes only**.
