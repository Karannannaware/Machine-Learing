# Machine-Learing
👉 “All my hands-on machine learning practice notebooks from Google Colab”
# 📘 Machine Learning Projects from Google Colab

# 🧾 Insurance Charges Prediction ML Project

This project predicts insurance charges based on factors like age, gender, BMI, number of children, smoking habits, and region using a **Linear Regression** model.

---

## 📌 Problem Statement

Health insurance providers need a model to **predict medical charges** for customers based on personal and lifestyle information. This helps in better risk management and pricing policies.

---

## 📁 Dataset

- Source: [Kaggle – Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- Format: CSV (`insurance.csv`)
- Features:
  - `age` – Age of primary beneficiary
  - `sex` – Gender
  - `bmi` – Body Mass Index
  - `children` – Number of children/dependents
  - `smoker` – Smoking habit (yes/no)
  - `region` – Residential area
  - `charges` – Final insurance cost (Target variable)

---

## 🔧 Tools & Libraries

- Python
- NumPy, pandas
- Seaborn, Matplotlib
- scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

- Checked for missing values
- Encoded categorical features using LabelEncoder
- Visualized data using:
  - Heatmap for correlation
  - Pairplots for feature distribution

---

## 🧠 Model Used

- **Linear Regression** from `sklearn.linear_model`

---

## 📈 Evaluation Metrics

- Mean Squared Error (MSE)
- R² Score

---

## 📌 Results

| Metric         | Value         |
|----------------|---------------|
| R² Score       | ~0.75 – 0.80  |
| Mean Squared Error | Depends on data split, usually stable |

---

## 📦 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/insurance-ml-project.git

