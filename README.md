# 🎓 Student Performance Predictor for EduQuest Coaching

This project aims to help **EduQuest Coaching** identify students who may need additional academic support by predicting their final exam performance using machine learning techniques.  

By analyzing various factors such as attendance, prior exam scores, engagement, and demographics, this model supports early interventions and personalized learning strategies.

---

## 📁 Dataset Overview

The dataset includes **1000 student records** with the following features:
- Gender, Age, Parental Education, Family Income  
- Internet Access, Attendance Rate, Number of Absences  
- Homework Completion, Participation Score, Prior Exam Score  
- Extracurricular Involvement, Weekly Study Hours  
- Tutor Support, Final Exam Score (Target)

---

## 🧠 Model Objectives

1. **Regression Model**: Predict exact `final_exam_score`
2. **Classification Model**: Categorize students into:
   - **High Performer** (>= 80)
   - **Medium Performer** (60–79)
   - **Low Performer** (< 60)

---

## 📊 Key Visualizations

### 🎯 Final Performance Classification Distribution
![Screenshot 2025-06-20 152945](https://github.com/user-attachments/assets/bacfaed1-2f35-451a-9ab0-9d3eb40ce9f2)


### 📉 Confusion Matrix
![YBI1](https://github.com/user-attachments/assets/43ff2691-5b71-458a-a34b-365e9f5ed63e)


### 📈 Feature Importance
![YBI2](https://github.com/user-attachments/assets/6d910e8c-9872-4bed-af05-9bf82f0b568e)



---

## ⚙️ Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Google Colab
- Supervised Learning Algorithms (Random Forest, etc.)

---

## 🚀 How to Run

1. Upload the dataset to your Colab or local Jupyter Notebook
2. Run the notebook blocks in order
3. Visualizations and predictions will be generated at the end

---

## ✅ Results

- **Classification Accuracy**: ~87% (Random Forest Classifier)
- **Top Influencing Features**:
  - Previous Exam Score
  - Attendance Rate
  - Homework Completion Rate
  - Learning Hours per Week

---

## 📌 Future Improvements

- Add student feedback and psychological data
- Include time-series performance tracking
- Build a web dashboard for visual performance reports

