# synent-task8-studentperformance-bhupendrakumar
An end-to-end Data Science and Machine Learning project focused on analyzing and predicting student academic performance. The project includes data cleaning, exploratory data analysis (EDA), feature engineering, visualization, and predictive modeling using Linear Regression, Decision Tree, and Random Forest algorithms.

# 📚 Student Performance Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on analyzing and predicting student academic performance using Machine Learning techniques. The objective is to identify the factors that influence student scores and build predictive models capable of estimating academic performance based on demographic and educational attributes.

The project follows a complete Data Science workflow including Data Cleaning, Exploratory Data Analysis (EDA), Feature Engineering, Model Building, and Evaluation.

---

## 🎯 Problem Statement

Educational institutions often need insights into the factors affecting student performance. Understanding these factors can help improve learning outcomes and academic planning.

The objective of this project is to:

- Analyze student performance data.
- Identify important factors affecting academic achievement.
- Build predictive models to estimate student scores.
- Generate meaningful insights using data visualization and machine learning.

---

## 📂 Dataset Information

### Dataset Name

Students Performance Dataset

### Features

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

### Target Variable

Average Score

The Average Score is calculated using:

Average Score = (Math Score + Reading Score + Writing Score) / 3

---

## 🛠 Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

### Development Environment

- Jupyter Notebook

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Gender Distribution Analysis
- Lunch Type Analysis
- Test Preparation Analysis
- Score Distribution Analysis
- Correlation Analysis
- Feature Relationship Visualization

Visualizations were created using Matplotlib and Seaborn to better understand the dataset.

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

### Data Cleaning

- Checked Missing Values
- Removed Duplicate Records
- Verified Data Types

### Feature Engineering

- Created Average Score Feature

### Data Transformation

- Applied Label Encoding on Categorical Features
- Prepared Dataset for Machine Learning Models

---

## 🤖 Machine Learning Models

The following machine learning algorithms were implemented:

### 1. Linear Regression

A baseline regression model used for predicting student performance.

### 2. Decision Tree Regressor

Used to capture non-linear relationships between variables.

### 3. Random Forest Regressor

An ensemble learning algorithm used to improve prediction accuracy and reduce overfitting.

---

## ⚙️ Model Training

The dataset was split into:

- Training Data: 80%
- Testing Data: 20%

Train-Test Split was performed using Scikit-Learn.

---

## 📈 Model Evaluation

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

### Best Performing Model

Random Forest Regressor achieved the highest prediction performance among all implemented models.

---

## 🔍 Key Insights

- Students who completed the test preparation course generally achieved higher scores.
- Reading and Writing scores are highly correlated.
- Parental education level positively impacts student performance.
- Lunch type has a noticeable influence on academic outcomes.
- Ensemble learning models provide better prediction accuracy.

---

## 📷 Project Screenshots

### Dataset Overview

<img width="935" height="191" alt="image" src="https://github.com/user-attachments/assets/a728dd79-2ce3-4d70-a183-f95f6daab46f" />


### Gender Distribution

<img width="571" height="432" alt="download" src="https://github.com/user-attachments/assets/c691e8b2-03ad-4022-8b78-fc8e901660d0" />

### Score Distribution

<img width="552" height="413" alt="download" src="https://github.com/user-attachments/assets/863e36b4-abd3-49aa-899d-5a9d2abd32c5" />

### Correlation Heatmap

<img width="533" height="418" alt="download" src="https://github.com/user-attachments/assets/86426715-fc7e-4bfc-9dea-dfbec1e3015b" />

### Feature Importance

<img width="845" height="505" alt="download" src="https://github.com/user-attachments/assets/e777c2e8-8066-47cf-8089-c58eec2dbe69" />

### Model Comparison

<img width="335" height="166" alt="image" src="https://github.com/user-attachments/assets/1b9fb825-e089-44ab-881f-e2f811f9c415" />


---

## 📁 Project Structure

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

## 🚀 How to Run the Project

### Clone Repository

```bash
git clone https://github.com/bktechnology513/synent-task8-studentperformance-bhupendrakumar
```

### Navigate to Project Directory

```bash
cd synent-task8-studentperformance-bhupendrakumar
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Run All Cells

Execute all notebook cells sequentially.

---

## 📋 Requirements

Create a requirements.txt file containing:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 🎓 Internship Task Mapping

This project fulfills the following requirements:

✅ Data Cleaning

✅ Data Preprocessing

✅ Exploratory Data Analysis (EDA)

✅ Data Visualization

✅ Feature Engineering

✅ Train-Test Split

✅ Machine Learning Model Building

✅ Model Evaluation

✅ Result Interpretation

---

## 💡 Future Improvements

- Hyperparameter Tuning
- XGBoost Implementation
- Streamlit Deployment
- Interactive Dashboard
- Real-Time Student Performance Prediction

---

## 👨‍💻 Author

**Bhupendra Kumar**

Data Science Intern

Synent Technologies Internship Program

---

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.

---

## 📜 License

This project is developed for educational and internship purposes.
