# Student Academic Performance Prediction

## 📌 Project Overview

Students' academic performance is lower than expected. The school needs to understand the main factors affecting students' performance and identify students who may need support.

This project analyzes student performance data using **Python, SQL, Matplotlib, and Machine Learning**.

## 🎯 Objectives

- Analyze students' academic performance.
- Identify important factors associated with exam scores.
- Visualize performance patterns.
- Use SQL to query student data.
- Build Machine Learning models to predict exam scores.
- Compare model performance.
- Identify students who may need support.
- Provide personalized advice.

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- SQLite / SQL
- Scikit-learn
- Google Colab / Jupyter Notebook

## 📊 Dataset

The dataset contains student-related factors such as:

- Hours Studied
- Attendance
- Previous Scores
- Sleep Hours
- Motivation Level
- Tutoring Sessions
- Parental Involvement
- Access to Resources
- Teacher Quality
- Peer Influence
- Physical Activity
- Internet Access
- Exam Score

## 📈 Visualization

Matplotlib is used to visualize:

- Exam Score Distribution
- Hours Studied vs Exam Score
- Attendance vs Exam Score
- Feature Importance
- Actual vs Predicted Scores

## 🗄️ SQL Analysis

SQLite and SQL are used to:

- Calculate average exam scores.
- Find students with low exam scores.
- Analyze study hours and exam scores.
- Analyze attendance and academic performance.

## 🤖 Machine Learning

Two regression models are used:

### Linear Regression

A baseline model for predicting exam scores.

### Random Forest Regressor

A stronger model that can capture non-linear relationships between student factors and exam performance.

Models are evaluated using:

- MAE
- RMSE
- R² Score

## ⚠️ Risk Assessment

Based on the predicted exam score:

- **High Risk:** below 60
- **Medium Risk:** 60–69
- **Low Risk:** 70 or above

## 💡 Personalized Advice

The system can provide recommendations based on student data, such as:

- Improving attendance.
- Increasing study time gradually.
- Reviewing weak topics.
- Maintaining a regular sleep schedule.
- Getting additional academic support.
- Setting small study goals.
- Using available learning resources effectively.

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
SQL Analysis
   ↓
Data Visualization
   ↓
Feature Preparation
   ↓
Train / Test Split
   ↓
Machine Learning
   ↓
Model Evaluation
   ↓
Prediction
   ↓
Risk Assessment
   ↓
Personalized Advice
```

## 🚀 How to Run

1. Open the project in Google Colab or Jupyter Notebook.
2. Upload the CSV dataset.
3. Make sure the filename matches the Python code.
4. Run the notebook cells in order.
5. Review the analysis, visualizations, SQL results, model performance, predictions, and recommendations.

## 📁 Project Structure

```text
Student-Performance-Project/
│
├── StudentPerformanceFactors.csv
├── student_performance.ipynb
└── README.md
```

## 👨‍💻 Conclusion

This project combines Data Analysis, SQL, Visualization, and Machine Learning to understand factors associated with academic performance, predict exam scores, identify students who may need support, and provide personalized recommendations.

**Predict → Assess → Explain → Recommend**
