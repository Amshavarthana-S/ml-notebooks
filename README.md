#  Rock vs Mine Prediction using Machine Learning

A machine learning project that predicts whether an underwater object is a **Rock** or a **Mine** based on sonar signal data, using Logistic Regression.

## Project Overview

Sonar emits sound waves underwater and measures the echoes. The pattern differs depending on whether the object is a rock or a metal mine. This model trains on 60 sonar frequency readings to classify the object.

- **R** → Rock  
- **M** → Mine

---

## 📂 Dataset

- **File:** `sonar data.csv`
- **Rows:** 208 samples  
- **Columns:** 60 numerical features + 1 label  
- **Classes:** Mine (M): 111 | Rock (R): 97

---

## 🛠️ Technologies Used

- Python 3
- NumPy
- Pandas
- Scikit-learn
- Google Colab

---

## 📊 Model Performance

| Dataset       | Accuracy |
|---------------|----------|
| Training Data | 83.4%    |
| Test Data     | 76.2%    |

---
