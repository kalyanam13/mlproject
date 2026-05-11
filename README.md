# 🎓 Student Performance Prediction - End-to-End Machine Learning Project

## 📌 Project Overview

This project is an End-to-End Machine Learning Project built using Python.  
The main objective of this project is to predict a student's **Math Score** based on different features such as:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

This project follows a complete Machine Learning pipeline from Data Ingestion to Model Training and Evaluation.

---

# 🚀 Project Workflow

The complete workflow of this project includes:

1. Data Ingestion  
2. Data Transformation  
3. Model Training  
4. Model Evaluation  
5. Saving Model and Preprocessor  

---

# 📂 Project Structure

```bash
MLProject/
│
├── artifacts/
│   ├── train.csv
│   ├── test.csv
│   ├── data.csv
│   ├── model.pkl
│   └── preprocessor.pkl
│
├── notebook/
│   └── data/
│       └── stud.csv
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline/
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── requirements.txt
├── setup.py
└── README.md