# 🫀 Heart Disease Prediction using Machine Learning

## 📌 Overview
This project predicts the likelihood of heart disease in patients based on medical attributes such as age, cholesterol levels, blood pressure, and other health indicators.  
It uses **Python** and **Machine Learning algorithms** to train a predictive model and evaluate its performance.

---

## 📂 Dataset
- **File:** `heart.csv`
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Shape:** 303 rows × 14 columns  
- **Target Column:** `target` (1 = Disease, 0 = No Disease)

---

## 📊 Features
| Feature | Description |
|---------|-------------|
| `age` | Age of the patient |
| `sex` | Gender (1 = Male, 0 = Female) |
| `cp` | Chest pain type (0–3) |
| `trestbps` | Resting blood pressure (mm Hg) |
| `chol` | Serum cholesterol (mg/dl) |
| `fbs` | Fasting blood sugar > 120 mg/dl (1 = True, 0 = False) |
| `restecg` | Resting ECG results (0–2) |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina (1 = Yes, 0 = No) |
| `oldpeak` | ST depression induced by exercise |
| `slope` | Slope of the peak exercise ST segment |
| `ca` | Number of major vessels colored by fluoroscopy (0–3) |
| `thal` | Thalassemia (1 = Normal, 2 = Fixed defect, 3 = Reversible defect) |
| `target` | Heart disease presence (1 = Yes, 0 = No) |

---

## ⚙️ Installation & Requirements
Make sure you have Python installed, then install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn
