# Student Placement Salary Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting student placement salaries using Machine Learning techniques. The objective is to analyze how academic performance, technical skills, internships, and project experience influence salary packages offered to students.

The project applies regression algorithms to estimate salary values based on multiple student-related features.

---

# 📊 Dataset Information

### Dataset Name
Student Placement Salary Dataset

### Dataset Source
https://www.kaggle.com/datasets/amaymishra11/student-placement-and-salary-dataset-skills-based

### Dataset Type
Regression Dataset

### Dataset Shape
9,000 rows and multiple feature columns

### Target Variable
salary_lpa (Salary offered in Lakhs Per Annum)

---

# 🛠️ Proposed Methodology & Models

## Type of Task
Supervised Learning – Regression

---

## Data Preprocessing
- Removed unnecessary columns
- Applied One-Hot Encoding using pd.get_dummies()
- Created a new feature called total_skills

---

## Feature Engineering
Combined technical skill features:
- Python Skill
- DSA Skill
- ML Skill
- Web Development Skill

to create:
- total_skills

---

# 🤖 Models Used

## 1. Linear Regression
Used as the baseline regression model.

## 2. Random Forest Regressor
Used for improved prediction accuracy and handling non-linear relationships.

---

# 📈 Evaluation Metrics

The models were evaluated using:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 📊 Results

| Model | R² Score |
|---|---|
| Linear Regression | 0.82 |
| Random Forest Regressor | 0.88 |

Random Forest achieved better prediction accuracy.

---

# 📉 Generated Visualizations

The notebook includes:
- CGPA vs Salary Scatter Plot
- Internship vs Salary Analysis
- Salary Distribution Histogram
- Actual vs Predicted Salary Plot
- Feature Importance Graph

---

# 🚀 How to Run the Project

1. Download the dataset file.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload the dataset CSV file.
4. Run all notebook cells sequentially.
5. View model outputs, graphs, and evaluation metrics.

---

# ✅ Conclusion

The project successfully predicts student placement salaries using Machine Learning regression models.

Among the models tested, Random Forest Regressor achieved the best performance with higher R² score and better predictive capability.
