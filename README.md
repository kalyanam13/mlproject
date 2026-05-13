# 🎓 Student Performance Prediction | End-to-End Machine Learning Project

# 📌 Project Overview

This is an **End-to-End Machine Learning Project** developed using **Python, Scikit-Learn, Flask, Pandas, NumPy, and Machine Learning Pipeline concepts**.

The objective of this project is to predict a student's **Math Score** based on several features such as:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

The project follows the complete lifecycle of a Machine Learning application starting from:

✅ Data Ingestion  
✅ Data Transformation  
✅ Model Training  
✅ Model Evaluation  
✅ Model Deployment using Flask  

---

# 🚀 Features

✨ End-to-End Machine Learning Pipeline  
✨ Data Ingestion and Data Transformation  
✨ Model Training and Evaluation  
✨ Flask Web Application  
✨ Beautiful Responsive User Interface  
✨ Real-Time Prediction System  
✨ Exception Handling and Logging  
✨ Modular Coding Structure  
✨ Pickle File Serialization  
✨ Production-Level Project Structure  

---

# 🧠 Machine Learning Workflow

The complete workflow of this project is:

## 1️⃣ Data Ingestion

- Read dataset from CSV file
- Split data into Train and Test datasets
- Store train and test datasets inside artifacts folder

---

## 2️⃣ Data Transformation

Performed various preprocessing techniques:

- Handling numerical and categorical features
- Standard Scaling
- One Hot Encoding
- Pipeline Creation using Scikit-Learn
- Column Transformer Implementation

---

## 3️⃣ Model Training

Different Machine Learning models were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- CatBoost Regressor
- AdaBoost Regressor

---

## 4️⃣ Model Evaluation

Evaluation metrics used:

- R² Score
- Mean Absolute Error
- Mean Squared Error

Best model selected automatically based on performance.

---

## 5️⃣ Model Deployment

- Flask used for Web Application
- User inputs data through UI
- Model predicts Maths Score instantly
- Prediction displayed dynamically on screen

---

# 🖥️ Web Application

The project also includes a beautiful and responsive Flask web application where users can:

✅ Enter Student Details  
✅ Submit Input Data  
✅ Get Real-Time Maths Score Prediction  

---

# 📂 Project Structure

```bash
MLProject/
│
├── artifacts/
│   ├── data.csv
│   ├── train.csv
│   ├── test.csv
│   ├── model.pkl
│   └── preprocessor.pkl
│
├── notebook/
│   └── data/
│       └── stud.csv
│
├── src/
│   │
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline/
│   │   └── predict_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
│   ├── home.html
│   └── index.html
│
├── app.py
├── requirements.txt
├── setup.py
└── README.md
```

---

# ⚙️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computation |
| Scikit-Learn | Machine Learning |
| Flask | Web Framework |
| HTML/CSS | Frontend UI |
| Bootstrap | Responsive Design |
| Pickle | Model Serialization |

---

# 📊 Dataset Information

Dataset contains student-related information such as:

- Gender
- Ethnicity
- Parent Education
- Lunch Type
- Test Preparation
- Reading Score
- Writing Score

Target Variable:

🎯 **Math Score**

---

# 🛠️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/MLProject.git
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

---

## Activate Environment

### Windows

```bash
venv\Scripts\activate
```

### Mac/Linux

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run Application

```bash
python app.py
```

Then open browser:

```bash
http://127.0.0.1:5000/predict
```

---

# 📸 Project Screenshots

## 🌟 Modern Flask Web Application UI

- Beautiful AI-style interface
- Responsive Design
- Real-Time Prediction System

---

# 📈 Future Improvements

- Docker Deployment
- Cloud Deployment on AWS/Azure
- User Authentication
- Database Integration
- Model Monitoring
- CI/CD Pipeline

---

# 💡 Learning Outcomes

Through this project, I learned:

✅ End-to-End ML Pipeline Development  
✅ Data Preprocessing Techniques  
✅ Feature Engineering  
✅ Model Selection and Evaluation  
✅ Flask Deployment  
✅ Exception Handling  
✅ Logging System  
✅ Modular Coding Practices  
✅ Frontend + Backend Integration  

---

# 🙋‍♂️ Author

## Kalyanam Chakrawarty

Machine Learning Enthusiast | Data Science Learner | AI Developer

---

# ⭐ If you like this project

Please give this repository a ⭐ on GitHub.

---

# 🚀 Thank You

Thank you for visiting this project.

Feel free to fork, improve, and contribute ✨