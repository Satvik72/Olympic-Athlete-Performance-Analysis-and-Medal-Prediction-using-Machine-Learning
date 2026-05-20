# 🏅 Olympic Athlete Performance Analysis and Medal Prediction

## 📌 Project Overview
This project focuses on analyzing Olympic athlete data and building machine learning models to predict whether an athlete will win a medal or not. The project follows a complete data science pipeline including data preprocessing, exploratory data analysis (EDA), model building, evaluation, and final prediction.

---

## 🎯 Objectives
- Analyze athlete demographics and Olympic trends
- Identify patterns influencing medal outcomes
- Build multiple machine learning models for prediction
- Compare models using multiple evaluation metrics
- Select the best model for final prediction

---

## 📂 Dataset
- Dataset: Olympic Athlete Events Dataset
- Features include:
  - Age
  - Gender (Sex)
  - Height
  - Weight
  - Year
  - Sport
  - Event
  - Medal

---

## 🧹 Data Preprocessing
- Handled missing values using median imputation
- Removed duplicate records
- Converted categorical variables using Label Encoding
- Created a new target variable:
  - `Medal_Won` → 1 (Medal), 0 (No Medal)

---

## 📊 Exploratory Data Analysis (EDA)
Performed detailed EDA using visualization techniques:
- Distribution plots (Age, Height, Weight)
- Pairplots for feature relationships
- Heatmap for correlation analysis
- Countplots for medal distribution
- Boxplots for feature comparison

---

## 🤖 Machine Learning Models
Implemented and compared the following models:
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Naive Bayes (GaussianNB)
- Logistic Regression

---

## 📈 Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score

Additionally:
- ROC Curve and AUC were used for performance analysis
- Confusion Matrix for classification results
- Feature Importance for model interpretability

---

## 🏆 Best Model Selection
The best model was selected based on the **average of all evaluation metrics**:
- Accuracy
- Precision
- Recall
- F1 Score

This ensured a balanced and reliable model selection.

---

## 🔮 Prediction System
A final prediction system was built using the best-performing model.

### Input Features:
- Sex (0 = Female, 1 = Male)
- Age
- Height
- Weight
- Year

### Output:
- Medal Won 🏅
- No Medal ❌

---

## 📊 Visualizations Included
- Confusion Matrix
- ROC Curve
- Feature Importance Graph
- Model Comparison Chart
- EDA Visualizations (heatmaps, pairplots, etc.)

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📄 Project Report
You can view the detailed report here:  
👉 [Download Report](./Olympic_Medal_Prediction_Report.pdf)

---

## 🚀 How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/pklayal/Olympic-Athlete-Performance-Analysis-and-Medal-Prediction-using-Machine-Learning.git
