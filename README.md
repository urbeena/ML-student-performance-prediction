## End to END ML PROJECT student performance prediction


🎓 ML Student Performance Prediction
📌 Project Overview

This project is a Machine Learning–based web application that predicts a student’s academic performance score using demographic and academic attributes.
It demonstrates an end-to-end ML workflow, from data preprocessing and model training to deployment-ready inference using Flask.

🚀 Features

Predicts student performance using a trained ML model

Modular and scalable ML pipeline

Flask-based web interface

Handles categorical and numerical features

Ready for cloud deployment

🧠 Machine Learning Workflow

Data Ingestion

Data Preprocessing

Feature Engineering

Model Training

Model Serialization

Prediction Pipeline

Web Deployment

🛠️ Tech Stack
Programming Language

Python

Data Science & ML

Pandas

NumPy

Scikit-learn

CatBoost

Web Framework

Flask

Tools

Git & GitHub

Pickle

📂 Project Structure
ML-student-performance-prediction/
│
├── artifacts/               # Saved models & preprocessors
├── notebook/                # EDA & experiments
├── src/
│   ├── components/          # Data ingestion & transformation
│   ├── pipeline/            # Training & prediction pipelines
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/               # HTML templates
│   ├── index.html
│   └── home.html
│
├── application.py           # Flask application
├── requirements.txt
├── setup.py
└── README.md

📊 Input Features

Gender

Race/Ethnicity

Parental level of education

Lunch type

Test preparation course

Reading score

Writing score

📈 Output

Predicted student performance score

▶️ How to Run the Application
Step 1: Clone the Repository
git clone https://github.com/urbeena/ML-student-performance-prediction.git
cd ML-student-performance-prediction

Step 2: Create and Activate Virtual Environment
python -m venv env
env\Scripts\activate

Step 3: Install Dependencies
pip install -r requirements.txt

Step 4: Run the Flask App
python application.py

Step 5: Open in Browser
http://localhost:5000

🌐 Application Routes

/ → Home page

/predictdata → Prediction endpoint

🎯 Use Cases

Educational analytics

Student performance assessment

Machine learning portfolio project
