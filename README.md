# MENTHEALTH
# 🧠 Mental Health Risk Predictor

A Machine Learning project that predicts whether a student is at risk of stress or depression based on their lifestyle and academic data.

---

## 📌 Project Overview

Mental health is a growing concern among students. This project uses real student survey data to build a classification model that can identify students who may be at risk of depression, anxiety, or panic attacks — based on factors like their CGPA, year of study, age, and whether they are seeking treatment.

---

## 🔄 How It Works
```
Student Lifestyle Data → Data Cleaning → Feature Engineering → ML Model → Risk Prediction
```

---

## 📊 Dataset

- **Source:** [Kaggle — Student Mental Health Dataset](https://www.kaggle.com/datasets/shariful07/student-mental-health)
- **Size:** 101 student records
- **Features used:**

| Feature | Description |
|---------|-------------|
| Gender | Male / Female |
| Age | Student age |
| Course | Field of study |
| Year of Study | 1st, 2nd, 3rd, or 4th year |
| CGPA | Academic performance range |
| Marital Status | Married or not |
| Seeking Treatment | Currently getting help or not |

- **Target Label:** `at_risk` — 1 if student has depression, anxiety, or panic attacks. 0 if not.

---

## 🤖 ML Model

- **Algorithm:** Random Forest Classifier
- **Train / Test Split:** 80% training, 20% testing
- **Libraries:** `scikit-learn`, `pandas`, `matplotlib`, `seaborn`

---

## 📈 Results

- Accuracy score on test data
- Confusion matrix showing correct vs wrong predictions
- Feature importance chart — shows which factors influence mental health risk the most

---

## 🗂️ Project Structure
```
mental-health-predictor/
│
├── mental_health_predictor.ipynb   ← Main Jupyter Notebook
├── mental_health.csv               ← Dataset (download from Kaggle)
└── README.md                       ← Project description (this file)
```

---

## ▶️ How to Run

1. Clone or download this repository
2. Download `mental_health.csv` from [Kaggle](https://www.kaggle.com/datasets/shariful07/student-mental-health) and place it in the project folder
3. Install the required libraries:
```bash
   pip install pandas matplotlib seaborn scikit-learn
```
4. Open the notebook:
```bash
   jupyter notebook mental_health_predictor.ipynb
```
5. Run all cells from top to bottom

---

## 🔍 Key Findings

- Students in higher years of study show higher mental health risk
- CGPA and seeking treatment are strong indicators of mental health status
- A significant portion of students show signs of anxiety or depression

---

## 💡 Future Improvements

- Add more features like sleep hours, screen time, and physical activity
- Try other models like Logistic Regression or XGBoost and compare accuracy
- Build an interactive input form using `ipywidgets`
- Use a larger, more diverse dataset

---

## ⚠️ Disclaimer

This project is built for **educational purposes only**. It is not a substitute for professional mental health advice or diagnosis. If you or someone you know is struggling, please seek help from a qualified mental health professional.

---

## 👤 Author

Made with ❤️ by Vansh Sharma
