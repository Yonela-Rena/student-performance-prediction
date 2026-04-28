# 🎓 Student Performance Prediction

## 📌 Project Overview
This project uses Machine Learning (Linear Regression) to predict students’ final grades (G3) based on study habits, academic history, and personal factors.

The goal is to understand which factors influence student performance and build a predictive model that estimates final grades with reasonable accuracy.

---

## 📂 Project Structure
student-performance-prediction/
│
├── data/
│   └── student_data.csv
│
├── notebook/
│   ├── analysis.ipynb
│   └── analysis_v2.ipynb
│
├── grade_distribution.png
├── study_vs_grade.png
└── README.md

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Dataset
The dataset contains **395 student records** with **33 features**, including:

- Demographics (age, gender, address)  
- Family background  
- Study habits (study time, failures)  
- Attendance (absences)  
- Academic performance (G1, G2, G3)  

---

## 🧠 Features Used
The model was trained using selected features that are most relevant to student performance:

- Study time  
- Number of past failures  
- Absences  

These features were chosen because they have a direct impact on academic outcomes.

---

## ▶️ How to Run
1. Clone the repository  
2. Open the notebook in VS Code or Jupyter  
3. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
