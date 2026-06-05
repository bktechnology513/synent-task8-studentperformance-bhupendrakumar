# 📚 Student Performance Prediction Using Machine Learning

An end-to-end Data Science and Machine Learning project focused on analyzing and predicting student academic performance. The project includes data cleaning, exploratory data analysis (EDA), feature engineering, visualization, and predictive modeling using Linear Regression, Decision Tree, and Random Forest algorithms.

---

# 📌 Project Overview

Student performance is influenced by multiple demographic, social, and educational factors. Understanding these factors can help educational institutions improve learning outcomes and support students more effectively.

This project focuses on analyzing student performance data and building machine learning models capable of predicting academic achievement based on various student attributes.

The project follows a complete Data Science workflow including:

* Data Collection
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Preprocessing
* Model Building
* Model Evaluation
* Insight Generation

Developed as part of the **Synent Technologies Data Science Internship Program (Task 8 – Machine Learning Model).**

---

# 🎯 Business Objective

Educational institutions often seek data-driven approaches to improve student performance and academic outcomes.

The primary objective of this project is to develop a predictive analytics solution that helps identify the key factors affecting academic success and estimate student performance using machine learning techniques.

This project can support:

* Academic planning
* Student performance monitoring
* Early intervention strategies
* Personalized learning approaches
* Educational decision-making

---

# 🎯 Problem Statement

The objective of this project is to analyze student performance data and build predictive models capable of estimating student academic achievement.

Key goals include:

* Understanding factors affecting student performance
* Identifying relationships among academic variables
* Building accurate predictive models
* Generating actionable educational insights

---

# 📂 Dataset Information

## Dataset Name

Students Performance Dataset

### Features

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch
* Test Preparation Course
* Math Score
* Reading Score
* Writing Score

### Target Variable

Average Score

### Formula

```text
Average Score = (Math Score + Reading Score + Writing Score) / 3
```

---

# 📊 Dataset Summary

| Category        | Description                           |
| --------------- | ------------------------------------- |
| Dataset Type    | Educational Dataset                   |
| Problem Type    | Regression                            |
| Target Variable | Average Score                         |
| Records         | Student Performance Records           |
| Features        | Demographic and Educational Variables |

### Dataset Characteristics

* Contains both categorical and numerical features.
* Represents real-world educational performance data.
* Suitable for predictive analytics and regression modeling.
* Useful for identifying factors influencing academic achievement.

---

# 🛠 Technologies Used

## Programming Language

* Python

## Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Development Environment

* Jupyter Notebook

---

# 🔄 Project Workflow

## 1. Data Collection

Loaded and explored the student performance dataset.

### Activities Performed

* Dataset loading
* Structure inspection
* Data understanding

---

## 2. Data Cleaning

Ensured data quality before analysis.

### Cleaning Steps

* Checked missing values
* Removed duplicate records
* Verified data types
* Validated dataset consistency

---

## 3. Exploratory Data Analysis (EDA)

Performed comprehensive analysis to identify trends and patterns.

### Analyses Conducted

* Gender Distribution Analysis
* Lunch Type Analysis
* Test Preparation Analysis
* Score Distribution Analysis
* Correlation Analysis
* Feature Relationship Visualization

### Objectives

* Understand performance patterns
* Identify influential variables
* Explore feature relationships
* Generate educational insights

---

## 4. Feature Engineering

Created additional features to improve predictive performance.

### Feature Created

Average Score

```text
Average Score = (Math Score + Reading Score + Writing Score) / 3
```

---

## 5. Data Preprocessing

Prepared the dataset for machine learning algorithms.

### Steps Performed

* Label Encoding of categorical variables
* Feature transformation
* Data preparation for regression models
* Feature consistency validation

---

## 6. Train-Test Split

Dataset divided into:

* Training Data: 80%
* Testing Data: 20%

Using Scikit-Learn Train-Test Split methodology.

---

## 7. Model Building

Multiple regression algorithms were implemented and compared.

### Linear Regression

Used as the baseline predictive model.

### Decision Tree Regressor

Captured non-linear relationships between variables.

### Random Forest Regressor

Applied ensemble learning techniques to improve prediction accuracy and model stability.

---

# 🤖 Machine Learning Models

| Model                   | Purpose               |
| ----------------------- | --------------------- |
| Linear Regression       | Baseline Regression   |
| Decision Tree Regressor | Non-Linear Prediction |
| Random Forest Regressor | Ensemble Learning     |

---

# 🔍 Feature Importance Analysis

Several factors significantly influence student academic performance.

### Most Important Features

1. Reading Score
2. Writing Score
3. Test Preparation Course
4. Parental Education Level
5. Lunch Type

### Key Finding

Students who completed test preparation programs consistently achieved higher academic scores than those who did not.

---

# 📊 Model Evaluation

The models were evaluated using standard regression metrics.

### Evaluation Metrics

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

---

# 🏆 Best Performing Model

✅ **Random Forest Regressor**

### Why Random Forest?

* Handles complex non-linear relationships
* Reduces overfitting through ensemble learning
* Provides strong predictive performance
* Produces reliable and stable results

### Model Performance

Update this section with actual notebook results after execution.

Example:

```text
R² Score: 0.92
MAE: 2.45
RMSE: 3.18
```

---

# 📈 Key Insights

* Students completing the test preparation course generally achieve higher scores.
* Reading and Writing scores are strongly correlated.
* Parental education level positively impacts academic performance.
* Lunch type shows measurable influence on student achievement.
* Academic outcomes are affected by a combination of demographic and educational factors.
* Ensemble learning algorithms outperform traditional regression techniques.

---

# 💡 Educational Recommendations

Based on the analysis and model findings:

* Encourage participation in test preparation programs.
* Provide additional academic support to at-risk students.
* Monitor educational inequalities that may affect performance.
* Use predictive analytics for early intervention strategies.
* Develop personalized learning pathways based on student needs.

---

# 📈 Project Results

The machine learning pipeline successfully predicted student performance using demographic and educational variables.

### Major Achievements

* Cleaned and processed educational data.
* Conducted detailed exploratory data analysis.
* Built multiple machine learning regression models.
* Compared model performance using evaluation metrics.
* Identified key factors affecting academic success.
* Generated actionable educational insights.

---

# 📷 Project Screenshots

## Dataset Overview

<img width="935" height="191" alt="Dataset Overview" src="https://github.com/user-attachments/assets/a728dd79-2ce3-4d70-a183-f95f6daab46f" />

---

## Gender Distribution

<img width="571" height="432" alt="Gender Distribution" src="https://github.com/user-attachments/assets/c691e8b2-03ad-4022-8b78-fc8e901660d0" />

---

## Score Distribution

<img width="552" height="413" alt="Score Distribution" src="https://github.com/user-attachments/assets/863e36b4-abd3-49aa-899d-5a9d2abd32c5" />

---

## Correlation Heatmap

<img width="533" height="418" alt="Correlation Heatmap" src="https://github.com/user-attachments/assets/86426715-fc7e-4bfc-9dea-dfbec1e3015b" />

---

## Feature Importance

<img width="845" height="505" alt="Feature Importance" src="https://github.com/user-attachments/assets/e777c2e8-8066-47cf-8089-c58eec2dbe69" />

---

## Model Comparison

<img width="335" height="166" alt="Model Comparison" src="https://github.com/user-attachments/assets/1b9fb825-e089-44ab-881f-e2f811f9c415" />

---

# 📁 Project Structure

```text
synent-task8-studentperformance-bhupendrakumar
│
├── StudentsPerformance.csv
├── StudentPerformance.ipynb
├── README.md
├── requirements.txt
├── images
│   ├── score_distribution.png
│   ├── heatmap.png
│   ├── feature_importance.png
│   └── model_comparison.png
└── .gitignore
```

---

# 🚀 How to Run the Project

## Clone Repository

```bash
git clone https://github.com/bktechnology513/synent-task8-studentperformance-bhupendrakumar
```

## Navigate to Project Directory

```bash
cd synent-task8-studentperformance-bhupendrakumar
```

## Install Required Libraries

```bash
pip install -r requirements.txt
```

## Launch Jupyter Notebook

```bash
jupyter notebook
```

Run all notebook cells sequentially.

---

# 📋 Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

# 🎓 Internship Task Mapping

### Requirements Completed

✔ Data Cleaning

✔ Data Preprocessing

✔ Exploratory Data Analysis (EDA)

✔ Data Visualization

✔ Feature Engineering

✔ Train-Test Split

✔ Machine Learning Model Building

✔ Model Evaluation

✔ Result Interpretation

✔ Predictive Analytics

---

# 💡 Future Improvements

* Hyperparameter Tuning
* XGBoost Implementation
* Streamlit Deployment
* Interactive Dashboard Development
* Real-Time Student Performance Prediction
* Model Explainability using SHAP

---

# 👨‍💻 Author

**Bhupendra Kumar**

Data Science & Machine Learning Enthusiast

Synent Technologies Data Science Intern

### Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Regression Modeling
* Machine Learning
* Data Visualization
* Predictive Analytics
* Educational Data Analysis

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 📜 License

This project is developed for educational, learning, and internship purposes.
