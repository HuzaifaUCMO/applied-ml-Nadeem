# Lab 5 – Ensemble Machine Learning (Wine Quality)

**Name:** Huzaifa Nadeem  
**Date:** April 11, 2025  

## 📚 Project Overview

This project explores ensemble classification techniques to predict red wine quality using physicochemical features. Ensemble models like Random Forests and Voting Classifiers were trained and evaluated to find the best-performing approach for generalization.

We used the [Wine Quality – Red Wine Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv) from the UCI Machine Learning Repository.

The goal was to classify wine into three quality categories: `low`, `medium`, and `high` using features like acidity, sugar, pH, alcohol, etc.

---

## 🔍 What’s Inside

- `ensemble-huzaifanadeem.ipynb` – Jupyter notebook with all steps:
  - Data loading and inspection
  - Preprocessing and feature engineering
  - Ensemble model training (Random Forest, Voting Classifier)
  - Evaluation with accuracy, F1-score, confusion matrix
  - Summary table of results and reflections

---

## 🧪 Models Used

- ✅ Random Forest Classifier (100 trees)
- ✅ Voting Classifier (Random Forest + Logistic Regression + KNN)

Both models were compared using test accuracy and F1-score.

---

## 📊 Results Summary

| Model                        | Test Accuracy | Test F1 Score |
|-----------------------------|---------------|----------------|
| Random Forest (100 trees)   | ✔️ Highest     | ✔️ Highest      |
| Voting (RF + LR + KNN)      | Good           | Slightly Lower |

---

## 💭 Key Takeaways

- Random Forest outperformed the others in both accuracy and F1 score.
- Voting Classifier added diversity but was slightly weaker overall.
- With more time, we could explore Gradient Boosting and tune hyperparameters.

---

## ▶️ How to Run Locally

1. **Clone the repository**  
   ```bash
   git clone https://github.com/YourUsername/your-repo-name.git
   cd your-repo-name

Create a virtual environment

bash
Copy
Edit
python -m venv .venv
.venv\\Scripts\\activate  # On Windows
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook
Open ensemble-huzaifanadeem.ipynb in VS Code or Jupyter Notebook.

📁 Files Included
ensemble-huzaifanadeem.ipynb – Main notebook

winequality-red.csv – Dataset

.venv/ – Local virtual environment (not pushed to GitHub)

requirements.txt – List of dependencies

📌 Notes
You may need to download the dataset directly if it’s not already included: Wine Quality (Red)