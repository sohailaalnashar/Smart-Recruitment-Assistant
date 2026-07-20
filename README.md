# 🎯 Smart Recruitment Assistant

## 💡 Project Overview
Companies often face high training costs and retention challenges when new hires leave shortly after joining[cite: 1]. The **Smart Recruitment Assistant** leverages Machine Learning to predict candidate job change intent[cite: 1], enabling recruiters to automatically filter applicants, identify stable talent, and make data-driven hiring decisions[cite: 1].

---

## 🛠️ Libraries & Technologies Used
* **Data Manipulation & Analysis:** `pandas`, `numpy`
* **Machine Learning & Modeling:** `scikit-learn` (`LogisticRegression`, `RandomForestClassifier`, `RandomizedSearchCV`)
* **Evaluation & Metrics:** `scikit-learn` (`accuracy_score`, `precision_score`, `recall_score`, `f1_score`, `confusion_matrix`)

---

## 📊 Model Results & Performance

Two classification models were evaluated to identify candidates likely to switch jobs[cite: 1]:

| Metric | Logistic Regression (Baseline) | Random Forest (Tuned - Final Model) |
| :--- | :---: | :---: |
| **Accuracy** | 71.0%[cite: 1] | **79.0%**[cite: 1] |
| **Precision** *(Job Changers)* | 44.2%[cite: 1] | **55.0%**[cite: 1] |
| **Recall** *(Job Changers)* | 64.0%[cite: 1] | **70.0%**[cite: 1] |
| **F1 Score** *(Job Changers)* | 52.3%[cite: 1] | **62.0%**[cite: 1] |

> **Key Takeaway:** **Random Forest** was chosen as the production model as it achieved superior performance across all metrics—especially Recall (70.0%), capturing more candidates intending to switch while minimizing false negatives[cite: 1].
