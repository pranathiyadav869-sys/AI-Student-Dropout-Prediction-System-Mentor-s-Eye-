<img width="2852" height="1630" alt="image" src="https://github.com/user-attachments/assets/e8c302ae-e366-4a43-895e-003b529833a3" /><!-- # SIH_Team_OG
This project builds an AI-driven system to predict student dropout risk using data like attendance, grades, engagement, and fee status. With feature engineering, a Random Forest model, and visual insights, it highlights at-risk students early, enabling educators to take proactive, data-driven interventions. -->
# 🎓 AI Student Dropout Prediction System (Mentor's Eye)

An AI-powered system designed to **predict student dropout risk** using academic, behavioral, and financial data.
It enables educators to identify at-risk students early and take **data-driven interventions**.

---

## 🚀 Features

* 📊 Predicts student risk levels (High / Medium / Low)
* 🧠 Machine Learning model (Random Forest)
* 📈 Feature engineering (engagement score, grade velocity)
* 📉 Interactive dashboard with trends & probabilities
* 🗂 SQLite database for student records
* 📝 Mentor notes system
* 🔄 What-if analysis (simulate improvements)

---

## 🧠 Machine Learning Pipeline

* Data preprocessing & encoding
* Feature Engineering:

  * Grade Velocity
  * Engagement Score
* Model: Random Forest Classifier
* Evaluation: Accuracy, Classification Report, Confusion Matrix
* Model persistence using Joblib

---

## 🏗️ Project Structure

```
├── app.py                      # Flask web application
├── train_model.py             # Model training script
├── predict.py                 # Prediction logic
├── generate_historical_data.py# Synthetic time-series data
├── migrate_data.py            # CSV → Database migration
├── database_setup.py          # DB schema setup
├── mentors_eye.db             # SQLite database
├── templates/
│   ├── index.html             # Dashboard UI
│   ├── login.html             # Login page
├── model files/
│   ├── student_dropout_model.joblib
│   ├── scaler.joblib
│   ├── label_encoder.joblib
│   ├── model_columns.joblib
├── data/
│   ├── project_student_data.csv
│   ├── project_student_data_historical.csv
```

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/student-dropout-ai.git
cd student-dropout-ai

pip install -r requirements.txt
```

---

## ▶️ How to Run

### 1️⃣ Train Model

```bash
python train_model.py
```

### 2️⃣ Generate Historical Data

```bash
python generate_historical_data.py
```

### 3️⃣ Setup Database

```bash
python database_setup.py
```

### 4️⃣ Migrate Data

```bash
python migrate_data.py
```

### 5️⃣ Run Application

```bash
python app.py
```

---

## 🔐 Login Credentials

```
Email: mentor@college.edu  
Password: password123
```

---

## 📊 Model Output

* Risk Level (High / Medium / Low)
* Probability distribution
* Key contributing factors:

  * Low attendance
  * Low scores
  * Fee issues
  * Declining performance

---

## 🧩 Tech Stack

* Python 🐍
* Flask 🌐
* Scikit-learn 🤖
* SQLite 🗄️
* HTML + Tailwind CSS 🎨
* Chart.js 📊

---
## 📸 Project Screenshots

### 🖥️ Dashboard Overview

![Dashboard](<img width="928" height="798" alt="image" src="https://github.com/user-attachments/assets/d39c2699-a910-4694-b89f-77f52a99f8e6" />
)

### 📊 Confusion Matrix

![Confusion Matrix](<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/27817a42-57fb-42c6-b261-de0d2baafae2" />
)

### 🔍 Student Risk Analysis

![Student Analysis]<img width="2852" height="1630" alt="image" src="https://github.com/user-attachments/assets/37e0f92a-4fb2-4fd5-95e2-c55fbbcdd5dd" />

### 📈 Performance Trends

![Performance Trends]<img width="2852" height="1630" alt="image" src="https://github.com/user-attachments/assets/aab345d6-7959-4ac4-bcc6-47971fef9aa4" />
<img width="2852" height="1630" alt="image" src="https://github.com/user-attachments/assets/6911151b-455d-48a0-b32f-b80c637ef007" />




## 💡 Future Improvements

* Deploy on cloud (AWS / Render)
* Add real-time student data integration
* Deep Learning models
* SMS / Email alerts for mentors
* Role-based authentication

---

## 👩‍💻 Author

**Pranathi Yadav**

**Snigdha Somaraju**

**K.V.Lakshman**

**Rishwanth**

**Sharan Thummala**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share!
