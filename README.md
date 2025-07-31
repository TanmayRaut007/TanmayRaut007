# 👋 Hi, I'm Tanmay Raut...! 

Welcome to my GitHub profile! I'm passionate about data science, machine learning, and building practical applications. Below are some of my featured projects, including a Flask web app for predicting employee retention using logistic regression.
  
---

## 🔍 Featured Project: Employee Retention Predictor 🧠

### 📌 Overview

This project predicts whether an employee is likely to leave the company or stay, based on factors like satisfaction level, salary, work hours, promotion status, and more. It's built using:

- ✅ Logistic Regression (Scikit-learn)
- ✅ Clean UI with Flask & HTML/CSS
- ✅ Real HR dataset
- ✅ Encoded categorical variables
- ✅ Model trained and deployed via web form

### 🚀 Features

- Predict employee churn based on 6 key HR features
- User-friendly web interface to test various scenarios
- Easily extendable with other models (SVM, Decision Tree, etc.)


---

### 🛠️ Tech Stack

- **Frontend**: HTML, CSS (Vanilla)
- **Backend**: Python, Flask
- **ML**: Scikit-learn, Pandas, NumPy
- **Visualization**: Seaborn, Matplotlib

---

### 📦 How to Run Locally

```bash
git clone https://github.com/yourusername/employee-retention-predictor.git
cd employee-retention-predictor
pip install -r requirements.txt
python app.py
```

Then go to `http://localhost:5000`

---

### 📁 File Structure

```
employee-retention-predictor/
├── app.py
├── model.pkl
├── HR_comma_sep.csv
├── templates/
│   └── index.html
├── static/ (optional for styles/images)
└── README.md
```

---

### 📈 Dataset Info

Used [HR Analytics Employee Dataset](https://www.kaggle.com/datasets) with the following columns:

- Satisfaction level
- Last evaluation
- Number of projects
- Average monthly hours
- Time spent in company
- Work accident
- Promotion in last 5 years
- Department
- Salary
- Left (Target)

---

### ✅ Model Accuracy

Achieved **~75.5%** accuracy using logistic regression. Feature selection was based on correlation analysis and business logic.

---

## 📫 Contact Me

- 📧 Email: tanmayraut60@gmail.com


---

⭐️ **Thanks for visiting! Feel free to fork, star, or contribute.**
