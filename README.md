# 🎓 Student Performance Analysis using Linear Regression

This project aims to analyze student performance in exams using a real-world dataset from [Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams).  
The goal is to predict **Math Scores** based on various student-related features using a **Supervised Learning** approach with **Linear Regression**.

---

## 📌 Dataset Overview

The dataset includes exam results for students in **Math**, **Reading**, and **Writing**, along with the following features:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type (Standard / Free-Reduced)
- Test Preparation Course (Completed or Not)

📂 Dataset: `StudentsPerformance.csv`  
🔗 Source: [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

---

## 🧠 Project Objectives

- Understand and explore the dataset using **pandas** and **seaborn**
- Preprocess categorical variables using **one-hot encoding**
- Apply **Linear Regression** from `sklearn` to predict `math score`
- Evaluate model performance using:
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)
  - R² Score
- Visualize predictions and residuals to understand model accuracy

---

## 📈 Methodology – Supervised Learning Steps

1. **Collecting Data**  
   Loaded dataset using `pandas`.

2. **Preparing the Data**  
   - Encoded categorical variables with `pd.get_dummies()`
   - Split data using `train_test_split`

3. **Choosing the Model**  
   - Applied `LinearRegression` from `sklearn.linear_model`

4. **Training the Model**  
   - Trained on 80% of the data

5. **Evaluating the Model**  
   - Printed MAE, MSE, and R² score
   - Visualized Actual vs Predicted scores

6. **Making Predictions**  
   - Predicted Math Scores for unseen test data

---

## 📊 Key Visualizations

- 📌 Distribution of Math Scores  
- 📌 Math Scores by Gender  
- 📌 Correlation Heatmap  
- 📌 Actual vs Predicted Scores  
- 📌 Residuals Distribution

---

## 🧪 Technologies Used

- Python 🐍
- Pandas
- Matplotlib & Seaborn
- Scikit-learn

---

## 📌 Conclusion

- Linear Regression provided a foundational approach to modeling student math scores.
- The model achieved reasonable accuracy with clear visual patterns between features and scores.
- Future improvements may include advanced models (e.g., Decision Trees, Random Forests) and hyperparameter tuning for better performance.

---

## ✅ Project Highlights

- ✔️ Real-world dataset analysis
- ✔️ Full ML pipeline with data cleaning, model training & evaluation
- ✔️ Clean and well-commented Jupyter Notebook
- ✔️ Visual storytelling using plots



